```mermaid
flowchart TD
    subgraph User
        A1([Start]) --> A2[Click Profile]
    end

    subgraph System
        B1[Fetch user profile data]
        B2[Display profile info]
    end

    A2 --> B1 --> B2 --> A3([End])
```
