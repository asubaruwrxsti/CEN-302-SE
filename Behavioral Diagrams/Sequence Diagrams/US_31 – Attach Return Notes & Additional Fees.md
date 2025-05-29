```mermaid
sequenceDiagram
    actor User
    participant UI
    participant System
    participant DB

    User->>UI: openReturnDetails()
    UI->>System: submitNotesAndFees()
    System->>DB: updateReservation(returnNotes, extraFees)
    activate DB
    DB-->>System: success
    deactivate DB

    System-->>UI: showSuccess()
    UI-->>User: confirmNotesAdded()
```
