```mermaid
flowchart TD
    User((Owner / Manager))
    UC28([View Upcoming Returns])
    UC04([View Reservations])

    User --> UC28
    UC28 -->|"«include»"| UC04
```
