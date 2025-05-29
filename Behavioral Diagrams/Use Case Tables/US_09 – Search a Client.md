| Field             | Description                                                                          |
| ----------------- | ------------------------------------------------------------------------------------ |
| Use Case ID       | US_09                                                                                |
| Name              | Search a Client                                                                      |
| Actor(s)          | Manager, Owner                                                                       |
| Description       | Search client by name, email, or phone.                                              |
| Preconditions     | Clients exist in the database.                                                       |
| Postconditions    | Matching client(s) are shown.                                                        |
| Main Flow         | 1. User enters search query. <br> 2. System searches database. <br> 3. Show results. |
| Alternative Flows | No match → Show "No client found" message.                                           |
