### Test Case ID: TC022  
**Target Description**: Verify that the cart icon or widget updates the item count and total price when multiple products are added  
**Suite**: Pizza Ordering  
**Type**: Functional / UI  
**Priority**: High  
---

#### Pre-conditions:
1. User is on the homepage: https://simply33food.com/en/  
2. At least two products are available for ordering  
3. Ordering iframe or modal can be opened via "Order" buttons  
4. Cart icon/widget is visible during ordering process  

---

#### Steps to Execute:

| Step | Action | Expected Result | Result | Bug Report ID |
|------|--------|------------------|--------|----------------|
| 1 | Click "Order" on the first product card and add it to the cart | Cart updates to show 1 item, correct product name and price | ⬜ |                |
| 2 | Close the modal and repeat for a second product | Cart now shows 2 items, correct total sum | ⬜ |                |
| 3 | Verify the cart icon or widget reflects the correct item count (e.g., badge or label) | Item counter increases with each addition | ⬜ |                |
| 4 | Open the cart (if applicable) | List of added products is visible with correct quantities and prices | ⬜ |                |

---

**Executor**: Petro Shutiak  
**Date**: 22.7.2025
