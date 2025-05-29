```mermaid
stateDiagram-v2
    [*] --> Available
    Available --> Reserved : Reservation made
    Reserved --> Rented : Rental started
    Rented --> Available : Rental completed
    Available --> Under_Maintenance : Sent for maintenance
    Under_Maintenance --> Available : Maintenance completed
    Reserved --> Under_Maintenance : Marked as unavailable
    Rented --> Under_Maintenance : Marked as unavailable
```
