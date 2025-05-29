```mermaid
flowchart TD
    User((Owner / Manager))
    UC14([Remove Reservation])
    UC13([Edit a Reservation])

    User --> UC14
    UC14 -.->|"«extend»"| UC13
```
