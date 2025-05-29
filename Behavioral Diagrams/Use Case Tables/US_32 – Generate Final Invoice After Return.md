| Field             | Description                                                                                                          |
| ----------------- | -------------------------------------------------------------------------------------------------------------------- |
| Use Case ID       | US_32                                                                                                                |
| Name              | Generate Final Invoice After Return                                                                                  |
| Actor(s)          | Manager, Owner                                                                                                       |
| Description       | Generate a PDF invoice including rental cost and additional fees.                                                    |
| Preconditions     | Return is completed with all notes/fees attached.                                                                    |
| Postconditions    | Invoice is generated and available for download.                                                                     |
| Main Flow         | 1. User selects return record. <br> 2. Clicks generate invoice. <br> 3. System compiles invoice and allows download. |
| Alternative Flows | Return incomplete → Show warning.                                                                                    |
