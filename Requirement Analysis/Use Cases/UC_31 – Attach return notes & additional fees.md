```mermaid
flowchart TD
    User((Owner / Manager))
    UC31([Attach Return Notes & Fees])
    UC24([Mark Reservation as Returned])

    User --> UC31
    UC31 -->|"«include»"| UC24
```
