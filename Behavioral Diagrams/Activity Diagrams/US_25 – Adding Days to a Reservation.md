```mermaid
flowchart TD
    subgraph User
        A1([Start]) --> A2[User logs in]
        A2 --> A3[Select active reservation]
        A3 --> A4[Enter number of days to extend]
    end

    subgraph System
        B1{Is extension possible?}
        B2[Show error: Conflicting reservation]
        B3[Update reservation with new dates and cost]
    end

    A4 --> B1
    B1 -- No --> B2 --> A4
    B1 -- Yes --> B3 --> A5([End])
```
