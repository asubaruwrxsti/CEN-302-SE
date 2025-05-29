```mermaid
flowchart TD
    subgraph User
        A1([Start]) --> A2[Select date and car filter]
    end

    subgraph System
        B1[Apply filter to calendar]
        B2{Matching cars available?}
        B3[Display filtered calendar]
        B4[Show No available cars message]
    end

    A2 --> B1 --> B2
    B2 -- Yes --> B3 --> A3([End])
    B2 -- No --> B4 --> A3
```
