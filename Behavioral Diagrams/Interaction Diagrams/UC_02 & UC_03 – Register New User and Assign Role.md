```mermaid
sequenceDiagram
    actor Admin
    participant System

    Admin->>System: createUser(name, email, password)
    System->>System: saveUserToDatabase()
    Admin->>System: assignRole(userId, role, branch)
    System-->>Admin: showConfirmation()
```
