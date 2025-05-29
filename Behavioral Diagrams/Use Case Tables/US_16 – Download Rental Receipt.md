| Field             | Description                                                                                                 |
| ----------------- | ----------------------------------------------------------------------------------------------------------- |
| Use Case ID       | US_16                                                                                                       |
| Name              | Download Rental Receipt                                                                                     |
| Actor(s)          | Manager, Owner                                                                                              |
| Description       | Download a PDF receipt for a specific rental.                                                               |
| Preconditions     | A completed reservation exists.                                                                             |
| Postconditions    | PDF receipt is downloaded.                                                                                  |
| Main Flow         | 1. User selects reservation. <br> 2. Clicks “Download Receipt”. <br> 3. System generates and downloads PDF. |
| Alternative Flows | Generation fails → Show error message.                                                                      |
