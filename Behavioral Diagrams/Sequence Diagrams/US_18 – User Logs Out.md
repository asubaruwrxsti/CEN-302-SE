```mermaid
sequenceDiagram
    actor User
    participant UI
    participant AuthSystem

    User->>UI: clickLogout()
    UI->>AuthSystem: invalidateSession()
    AuthSystem-->>UI: confirmLogout()
    UI-->>User: redirectToLoginPage()
```
