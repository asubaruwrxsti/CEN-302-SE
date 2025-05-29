```mermaid
flowchart TD
    Actor((Admin / Owner))
    UC12([Add Manager or Owner])
    UC13([Send Invitation Email])

    Actor --> UC12
    UC12 -->|"«include»"| UC13
```
