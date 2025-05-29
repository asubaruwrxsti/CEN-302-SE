```mermaid
sequenceDiagram
    actor Manager
    participant System

    Manager->>System: registerClient(name, id, phone)
    System->>System: saveClient()
    System-->>Manager: confirmRegistration()
```
