| Field             | Description                                                                                                     |
| ----------------- | --------------------------------------------------------------------------------------------------------------- |
| Use Case ID       | US_25                                                                                                           |
| Name              | Adding Days to a Reservation                                                                                    |
| Actor(s)          | Manager, Owner                                                                                                  |
| Description       | Extend the duration of a reservation.                                                                           |
| Preconditions     | Reservation is active or pending.                                                                               |
| Postconditions    | New end date and cost are updated.                                                                              |
| Main Flow         | 1. User selects reservation. <br> 2. Adds extra days. <br> 3. System recalculates cost and updates reservation. |
| Alternative Flows | Overlap with other bookings → System prevents extension.                                                        |
