```mermaid
flowchart TD
    Owner((Owner))
    UC23([View Manager Activity Report])
    UC22([View Activity Logs])

    Owner --> UC23
    UC23 -->|"«include»"| UC22
```
