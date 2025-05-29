```mermaid
flowchart TD
    User((Owner / Manager))
    UC05([View Calendar])
    UC04([View Reservations])

    User --> UC05
    UC05 -->|"«include»"| UC04
```
