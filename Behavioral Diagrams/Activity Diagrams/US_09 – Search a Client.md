```mermaid
flowchart TD
    subgraph User
        A1([Start]) --> A2[Enter client keyword]
    end

    subgraph System
        B1[Search client data]
        B2{Client found?}
        B3[Display client details]
        B4[Show Client not found message]
    end

    A2 --> B1 --> B2
    B2 -- Yes --> B3 --> A3([End])
    B2 -- No --> B4 --> A3
```
