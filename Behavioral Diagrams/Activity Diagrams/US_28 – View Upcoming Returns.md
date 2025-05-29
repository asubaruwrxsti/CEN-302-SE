```mermaid
flowchart TD
    subgraph User
        A1([Start]) --> A2[User logs in]
        A2 --> A3[Open Upcoming Returns view]
    end

    subgraph System
        B1{Are there any returns due?}
        B2[Show message: No upcoming returns]
        B3[Display return list]
    end

    A3 --> B1
    B1 -- No --> B2 --> A4([End])
    B1 -- Yes --> B3 --> A4
```
