```mermaid
flowchart TD
    subgraph Owner
        A1([Start]) --> A2[Owner logs in]
        A2 --> A3[Open activity logs page]
    end

    subgraph System
        B1{Are there any logs?}
        B2[Show message: No activity]
        B3[Display activity logs]
    end

    A3 --> B1
    B1 -- No --> B2 --> A4([End])
    B1 -- Yes --> B3 --> A4
```
