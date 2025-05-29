| Field             | Description                                                                                                                                         |
| ----------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| Use Case ID       | US_02                                                                                                                                               |
| Name              | Create a Reservation for a New Client                                                                                                               |
| Actor(s)          | Manager                                                                                                                                             |
| Description       | Manager creates a reservation by adding a new client.                                                                                               |
| Preconditions     | Client is not in the system.                                                                                                                        |
| Postconditions    | New client and reservation are saved.                                                                                                               |
| Main Flow         | 1. Manager inputs client details. <br> 2. System saves client. <br> 3. Manager selects car and reservation dates. <br> 4. System saves reservation. |
| Alternative Flows | Client info missing → System prompts to complete required fields.                                                                                   |
