```mermaid
flowchart TD
    User((Owner / Manager))
    UC34([View Car Maintenance History])
    UC20([View Car Inventory])

    User --> UC34
    UC34 -->|"«include»"| UC20
```
