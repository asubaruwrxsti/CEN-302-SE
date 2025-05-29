| Field             | Description                                                                      |
| ----------------- | -------------------------------------------------------------------------------- |
| Use Case ID       | US_13                                                                            |
| Name              | Edit a Reservation                                                               |
| Actor(s)          | Manager, Owner                                                                   |
| Description       | Allows the user to update a reservation’s start or end date.                     |
| Preconditions     | Reservation exists in pending status.                                            |
| Postconditions    | Reservation is updated.                                                          |
| Main Flow         | 1. User opens reservation. <br> 2. Modifies dates. <br> 3. System saves changes. |
| Alternative Flows | Invalid date range → Show validation error.                                      |
