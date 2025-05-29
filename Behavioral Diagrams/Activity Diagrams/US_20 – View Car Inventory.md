```mermaid
flowchart TD
    subgraph User
        A1([Start]) --> A2[User logs in]
        A2 --> A3[Go to car inventory page]
    end

    subgraph System
        B1{Are there cars in the branch?}
        B2[Show message: No cars]
        B3[Display car inventory with statuses]
    end

    A3 --> B1
    B1 -- No --> B2 --> A4([End])
    B1 -- Yes --> B3 --> A4
```
