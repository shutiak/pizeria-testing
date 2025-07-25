# Order Process Checklist - Simply 33

| # | Test Item                                                                 | Pass/Fail | Bug ID |
|---|---------------------------------------------------------------------------|-----------|--------|
| 1 | Cart is visible and accessible on all pages                              |✅      |        |
| 2 | User can successfully add pizza to the cart                              |✅     |        |
| 3 | Quantity update in the cart correctly updates the total price            |✅     |        |
| 4 | Deleting items from the cart works correctly                             |✅           |        |
| 5 | Cart preserves its state when navigating between pages                   |✅           |        |
| 6 | Total amount is displayed correctly                                      |✅           |        |
| 7 | Selecting a “1+1” deal automatically adds the second pizza               |❌           |        |
| 8 | The offer does not apply multiple times with only one pizza selected     |✅           |        |
| 9 | The second item in a 1+1 deal is displayed as 0 CZK in the cart          |✅           |        |
|10 | “Name” field is required                                                 |           |        |
|11 | “Phone” field accepts only valid numeric input                           |           |        |
|12 | “Email” field has proper validation                                      |           |        |
|13 | “Delivery address” field is required                                     |           |        |
|14 | Validation messages are displayed correctly for invalid input            |           |        |
|15 | Success message is shown after completing the order                      |           |        |
|16 | User cannot submit the order with an empty cart                          |           |        |
|17 | Refreshing the page does not clear the order/cart                        |           |        |
|18 | Checkout works properly in both English and Czech versions               |           |        |
|19 | Phone number without +420 is rejected (if applicable)                   |           |        |
|20 | Confirmation message appears after successful order                      |           |        |
|21 | Cart is cleared after the order                                          |           |        |
|22 | Admin receives the order (verify email or test notification)             |           |        |
