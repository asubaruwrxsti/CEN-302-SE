```mermaid
flowchart TD
    User((Owner / Manager))
    UC30([Filter Reservations])
    UC04([View Reservations])

    User --> UC30
    UC30 -->|"«include»"| UC04
```
