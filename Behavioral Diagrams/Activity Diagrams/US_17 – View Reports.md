```mermaid
flowchart TD
    subgraph User
        A1([Start]) --> A2[User logs in]
        A2 --> A3[Go to reports section]
    end

    subgraph System
        B1{Is there data available?}
        B2[Show message: No data]
        B3[Display report]
    end

    A3 --> B1
    B1 -- No --> B2 --> A4([End])
    B1 -- Yes --> B3 --> A4
```
