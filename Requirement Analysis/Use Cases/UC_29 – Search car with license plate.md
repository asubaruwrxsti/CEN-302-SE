```mermaid
flowchart TD
    User((Owner / Manager))
    UC29([Search Car by License Plate])
    UC20([View Car Inventory])

    User --> UC29
    UC29 -->|"«include»"| UC20
```
