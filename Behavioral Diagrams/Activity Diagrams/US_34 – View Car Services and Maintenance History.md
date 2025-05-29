```mermaid
flowchart TD
    subgraph User
        A1([Start]) --> A2[User logs in]
        A2 --> A3[Select car]
    end

    subgraph System
        B1{Does car have service history?}
        B2[Show message: No services]
        B3[Display service history]
    end

    A3 --> B1
    B1 -- No --> B2 --> A4([End])
    B1 -- Yes --> B3 --> A4
```
