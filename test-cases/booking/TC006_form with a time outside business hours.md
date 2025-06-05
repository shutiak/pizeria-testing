### Test Case ID: TC006  
**Target Description**: Attempt to submit reservation form with a time outside business hours  
**Suite**: Booking  
**Type**: Negative / Validation  
**Priority**: High  
---

#### Pre-conditions:
1. User is on the homepage: https://simply33food.com/  
2. Reservation form is visible and active  
3. The selected branch has defined business hours (e.g., 10:00–22:00)  

---

#### Steps to Execute:

| Step | Action | Expected Result | Pass | Fail | Bug Report ID |
|------|--------|------------------|------|------|----------------|
| 1 | Click the "Reserve Now" button | The page scrolls smoothly to the reservation section located on the same page |      |      |                |
| 2 | Input the following data into the reservation form:<br>• Name: "Petro"<br>• Email: "petroshutiak@gmail.com"<br>• Branch: "Pizza Grill House"<br>• Phone: "+420770601299"<br>• Date: a valid future date<br>• Time: "03:00"<br>• Guests: 4 | The "Time" field is marked as invalid (e.g., highlighted in red or a validation message appears) |      |      |                |
| 3 | Click the "Reserve" button | The form is not submitted. User is prompted to select a time within working hours |      |      |                |

---

**Executor**: Petro Shutiak  
**Date**: 4.6.2025  
