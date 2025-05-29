```mermaid
sequenceDiagram
    actor Admin
    participant System

    Admin->>System: login(email, password)
    System-->>Admin: redirectToDashboard()

    Admin->>System: createUser(name, email, password)
    System->>System: saveUser()

    Admin->>System: assignRole(userId, role, branchId)
    System-->>Admin: showAssignmentConfirmation()
```
