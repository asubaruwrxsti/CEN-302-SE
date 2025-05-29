```mermaid
flowchart TD
    subgraph Owner
        A1([Start]) --> A2[Owner logs in]
        A2 --> A3[Search for client]
    end

    subgraph System
        B1{Does client have rental history?}
        B2[Show message: No rentals]
        B3[Display rental history]
    end

    A3 --> B1
    B1 -- No --> B2 --> A4([End])
    B1 -- Yes --> B3 --> A4
```
