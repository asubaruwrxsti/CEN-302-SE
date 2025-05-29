```mermaid
stateDiagram-v2
  [*] --> Draft
  Draft --> PendingApproval : Submit
  PendingApproval --> Confirmed : Approved
  PendingApproval --> Cancelled : Rejected
  Confirmed --> Active : Start Date Reached
  Active --> Returned : Returned by Client
  Returned --> Closed : Final Invoice Issued
  Confirmed --> Cancelled : Cancel by Client
  Active --> Cancelled : Early Termination
  Cancelled --> [*]
  Closed --> [*]
```
