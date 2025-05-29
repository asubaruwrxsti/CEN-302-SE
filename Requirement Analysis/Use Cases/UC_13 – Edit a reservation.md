```mermaid
flowchart TD
    User((Owner / Manager))
    UC13([Edit Reservation])
    UC04([Select Car])

    User --> UC13
    UC13 -->|"«include»"| UC04
```
