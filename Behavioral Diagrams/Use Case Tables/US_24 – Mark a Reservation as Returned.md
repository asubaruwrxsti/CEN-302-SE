| Field             | Description                                                                             |
| ----------------- | --------------------------------------------------------------------------------------- |
| Use Case ID       | US_24                                                                                   |
| Name              | Mark a Reservation as Returned                                                          |
| Actor(s)          | Manager, Owner                                                                          |
| Description       | Update the reservation status when the car is returned.                                 |
| Preconditions     | Reservation is active.                                                                  |
| Postconditions    | Reservation is marked returned and car becomes available.                               |
| Main Flow         | 1. User selects reservation. <br> 2. Enters return info. <br> 3. System updates record. |
| Alternative Flows | Reservation not active → Deny update.                                                   |
