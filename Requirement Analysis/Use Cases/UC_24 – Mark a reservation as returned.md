```mermaid
flowchart TD
    User((Owner / Manager))
    UC24([Mark Reservation as Returned])
    UC25([Extend Reservation])

    User --> UC24
    UC24 -.->|"«extend»"| UC25
```
