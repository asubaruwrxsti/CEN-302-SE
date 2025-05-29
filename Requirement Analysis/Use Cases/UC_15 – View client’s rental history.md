```mermaid
flowchart TD
    Owner((Owner))
    UC15([View Client's Rental History])
    UC06([View Clients List])

    Owner --> UC15
    UC15 -->|"«include»"| UC06
```
