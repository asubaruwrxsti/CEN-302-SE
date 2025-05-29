
```mermaid
stateDiagram-v2
  [*] --> Pending
  Pending --> Completed : Payment Successful
  Pending --> Failed : Transaction Error
  Failed --> Retrying : Retry Triggered
  Retrying --> Completed : Success on Retry
  Retrying --> Failed : Retry Failed
  Completed --> Refunded : Refund Requested
  Refunded --> [*]
  Completed --> [*]
```