| Field             | Description                                                                                        |
| ----------------- | -------------------------------------------------------------------------------------------------- |
| Use Case ID       | US_36                                                                                              |
| Name              | Generate Invoice from Payment Page                                                                 |
| Actor(s)          | Owner                                                                                              |
| Description       | Generate a downloadable invoice using payment data.                                                |
| Preconditions     | Payment exists.                                                                                    |
| Postconditions    | Invoice is generated.                                                                              |
| Main Flow         | 1. Owner selects a payment. <br> 2. Clicks “Generate Invoice”. <br> 3. System creates PDF invoice. |
| Alternative Flows | Invoice generation fails → Show error.                                                             |
