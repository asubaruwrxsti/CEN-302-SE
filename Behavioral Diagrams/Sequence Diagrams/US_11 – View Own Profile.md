```mermaid
sequenceDiagram
    actor User
    participant UI
    participant System
    participant DB

    User->>UI: openProfile()
    UI->>System: fetchProfile()
    System->>DB: getUserProfile()
    activate DB
    DB-->>System: profileData
    deactivate DB

    System-->>UI: displayProfile()
    UI-->>User: showProfileDetails()
```
