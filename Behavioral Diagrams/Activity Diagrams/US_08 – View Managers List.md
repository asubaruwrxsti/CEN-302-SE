```mermaid
flowchart TD
    subgraph Owner
        A1([Start]) --> A2[Click Managers List]
    end

    subgraph System
        B1[Fetch manager data]
        B2{Any managers?}
        B3[Display managers list]
        B4[Show No managers message]
    end

    A2 --> B1 --> B2
    B2 -- Yes --> B3 --> A3([End])
    B2 -- No --> B4 --> A3
```
