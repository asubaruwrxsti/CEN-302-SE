```mermaid
flowchart TD
    subgraph User
        A1([Start]) --> A2[Click View Calendar]
    end

    subgraph System
        B1[Fetch reservations]
        B2{Any reservations?}
        B3[Show color-coded calendar]
        B4[Show blank calendar]
    end

    A2 --> B1 --> B2
    B2 -- Yes --> B3 --> A3([End])
    B2 -- No --> B4 --> A3
```
