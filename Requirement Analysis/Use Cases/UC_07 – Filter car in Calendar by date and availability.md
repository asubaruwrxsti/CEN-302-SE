```mermaid
flowchart TD
    User((Owner / Manager))
    UC07([Filter Calendar by Date and Availability])
    UC05([View Calendar])

    User --> UC07
    UC07 -->|"«include»"| UC05
```
