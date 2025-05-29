```mermaid
sequenceDiagram
    actor Admin
    participant System
    participant NotificationService

    Admin->>System: login(email, password)
    System-->>Admin: redirectToDashboard()

    Admin->>System: createOwner(name, email)
    System->>System: saveOwner()
    System->>NotificationService: sendOwnerInviteEmail()

    Admin->>System: createBranch(ownerId, location, plan)
    System->>System: saveBranch()

    Admin->>System: viewPlatformMetrics()
    System-->>Admin: displayMetrics()
```
