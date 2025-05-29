| Field             | Description                                                                                    |
| ----------------- | ---------------------------------------------------------------------------------------------- |
| Use Case ID       | US_22                                                                                          |
| Name              | View Activity Logs                                                                             |
| Actor(s)          | Owner                                                                                          |
| Description       | View a log of all actions performed within the branch.                                         |
| Preconditions     | Owner is authenticated.                                                                        |
| Postconditions    | Log history is displayed.                                                                      |
| Main Flow         | 1. Owner accesses logs page. <br> 2. System fetches logs. <br> 3. Display logs in list format. |
| Alternative Flows | No logs found → Show empty message.                                                            |
