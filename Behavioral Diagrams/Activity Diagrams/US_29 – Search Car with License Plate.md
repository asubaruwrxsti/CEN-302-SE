```mermaid
flowchart TD
    subgraph User
        A1([Start]) --> A2[User logs in]
        A2 --> A3[Go to car search page]
        A3 --> A4[Enter license plate]
    end

    subgraph System
        B1{Is car found?}
        B2[Show message: Car not found]
        B3[Display car details]
    end

    A4 --> B1
    B1 -- No --> B2 --> A5([End])
    B1 -- Yes --> B3 --> A5
```
