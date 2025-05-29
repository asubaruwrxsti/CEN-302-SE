```mermaid
flowchart TD
    Owner((Owner))
    UC33([Add Services & Maintenance])
    UC20([View Car Inventory])

    Owner --> UC33
    UC33 -->|"«include»"| UC20
```
