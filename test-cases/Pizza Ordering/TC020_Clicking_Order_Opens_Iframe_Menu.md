### Test Case ID: TC020  
**Target Description**: Verify that clicking the "Order" button opens the embedded ordering system (iframe or modal)  
**Suite**: Pizza Ordering  
**Type**: Functional  
**Priority**: High  
---

#### Pre-conditions:
1. User is on the homepage: https://simply33food.com/en/  
2. Menu section is fully loaded and at least one product card is visible  
3. Product card contains an "Order" button  

---

#### Steps to Execute:

| Step | Action | Expected Result | Result | Bug Report ID |
|------|--------|------------------|--------|----------------|
| 1 | Scroll to any product card in the menu section | "Order" button is visible on the card | ⬜ |                |
| 2 | Click the "Order" button | Embedded ordering interface (iframe or modal) opens above or next to the content | ⬜ |                |
| 3 | Observe the contents of the iframe/modal | Selected item or category is loaded correctly in the ordering system | ⬜ |                |
| 4 | Close the iframe/modal (if applicable) | Ordering interface closes and user returns to original page view | ⬜ |                |

---

**Executor**: Petro Shutiak  
**Date**: 22.7.2025

