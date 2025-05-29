```mermaid
flowchart TD
    subgraph Visitor
        A1([Start]) --> A2[Access public main page]
        A2 --> A3[View general platform information]
        A3 --> A4[Optionally choose to log in - see UC_01]
        A3 --> A5([End])
    end
```
