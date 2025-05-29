| Field             | Description                                                                           |
| ----------------- | ------------------------------------------------------------------------------------- |
| Use Case ID       | US_17                                                                                 |
| Name              | View Reports                                                                          |
| Actor(s)          | Owner, Admin                                                                          |
| Description       | View rental and revenue reports (branch-specific or platform-wide).                   |
| Preconditions     | User is authenticated.                                                                |
| Postconditions    | Reports are displayed.                                                                |
| Main Flow         | 1. User selects report type. <br> 2. System gathers data. <br> 3. Report is rendered. |
| Alternative Flows | Data fetch fails → Show error message.                                                |
