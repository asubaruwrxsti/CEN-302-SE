```mermaid
flowchart TD
    Owner((Owner))
    UC10([Search Manager])
    UC08([View Managers List])

    Owner --> UC10
    UC10 -->|"«include»"| UC08
```
