```mermaid
stateDiagram-v2
  [*] --> Created
  Created --> Active : Email Verified
  Active --> Suspended : Admin Action or Abuse
  Suspended --> Reactivated : Manual Reinstatement
  Reactivated --> Active
  Active --> Deactivated : User Request
  Deactivated --> [*]
  Suspended --> [*]
```
