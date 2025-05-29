
| Field             | Description                                                                                                                          |
| ----------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| Use Case ID       | US_03                                                                                                                                |
| Name              | Create a Reservation for an Existing Client                                                                                          |
| Actor(s)          | Manager                                                                                                                              |
| Description       | Manager books a car for an existing client.                                                                                          |
| Preconditions     | Client exists in the system.                                                                                                         |
| Postconditions    | Reservation is created for selected client.                                                                                          |
| Main Flow         | 1. Manager searches for client. <br> 2. Selects client. <br> 3. Selects car and reservation dates. <br> 4. System saves reservation. |
| Alternative Flows | Client not found → Manager retries search.                                                                                           |
