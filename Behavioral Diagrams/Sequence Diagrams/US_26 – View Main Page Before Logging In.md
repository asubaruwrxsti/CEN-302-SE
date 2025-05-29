```mermaid
sequenceDiagram
    actor Visitor
    participant UI
    participant System

    Visitor->>UI: openMainPage()
    UI->>System: loadPublicContent()
    System-->>UI: generalInfo(services, contact, login)
    UI-->>Visitor: displayPublicPage()
```
