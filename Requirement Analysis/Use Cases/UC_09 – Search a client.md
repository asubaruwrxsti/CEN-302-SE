```mermaid
flowchart TD
    User((Owner / Manager))
    UC09([Search Client])
    UC06([View Clients List])

    User --> UC09
    UC09 -->|"«include»"| UC06
```
