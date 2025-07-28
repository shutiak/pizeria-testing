### Test Case ID: TC021  
**Target Description**: Verify that a user can successfully add a product to the cart via the ordering interface  
**Suite**: Pizza Ordering  
**Type**: Functional  
**Priority**: High  
---

#### Pre-conditions:
1. User is on the homepage: https://simply33food.com/en/  
2. Product cards and "Order" buttons are visible in the menu section  
3. Ordering interface (iframe or modal) is functioning  
4. At least one product is available for ordering  

---

#### Steps to Execute:

| Step | Action | Expected Result | Result | Bug Report ID |
|------|--------|------------------|--------|----------------|
| 1 | Click the "Order" button on any product card | Ordering iframe/modal opens with item details | ⬜ |                |
| 2 | Select quantity or any required options (e.g. size, extras) | Selection is accepted without error | ⬜ |                |
| 3 | Click "Add to cart" or similar CTA | Item is added to the cart; confirmation appears | ⬜ |                |
| 4 | Open the cart (if separate) or observe cart widget | Cart displays the correct item with quantity and price | ⬜ |                |

---

**Executor**: Petro Shutiak  
**Date**: 22.7.2025
