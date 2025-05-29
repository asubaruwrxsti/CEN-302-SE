| Field             | Description                                                                                     |
| ----------------- | ----------------------------------------------------------------------------------------------- |
| Use Case ID       | US_05                                                                                           |
| Name              | View Calendar                                                                                   |
| Actor(s)          | Manager, Owner                                                                                  |
| Description       | Calendar view of all cars and their reservations.                                               |
| Preconditions     | User is logged in.                                                                              |
| Postconditions    | Calendar populated with data.                                                                   |
| Main Flow         | 1. User opens calendar. <br> 2. System fetches reservation data. <br> 3. Calendar is displayed. |
| Alternative Flows | API error → Show error message.                                                                 |