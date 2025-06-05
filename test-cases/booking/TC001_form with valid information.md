### Test Case ID: TC001  
**Target Description**: Submit a reservation form with valid information  
**Suite**: Booking  
**Type**: Functional  
**Priority**: High  
---

#### Pre-conditions:
1. User is on the homepage: https://simply33food.com/  
2. "Reserve Now" button is visible  
3. Reservation form is part of the homepage content  

---

#### Steps to Execute:

| Step | Action | Expected Result | Pass | Fail | Bug Report ID |
|------|--------|------------------|------|------|----------------|
| 1 | On the homepage, click the "Reserve Now" button | The page scrolls smoothly to the reservation section located on the same page |      |      |                |
| 2 | Input the following valid data into the reservation form:<br>• Name: "Petro"<br>• Email: "petroshutiak@gmail.com"<br>• Branch: "Pizza Grill House"<br>• Phone: "+420770601299"<br>• Date: any future date<br>• Time: available time<br>• Guests: 4<br>• Note: "birthday party" | All fields accept the input without displaying validation errors |      |      |                |
| 3 | Click the "Reserve" button | A success message is displayed confirming that the reservation was submitted |      |      |                |

---

**Executor**: Petro Shutiak  
**Date**: 4.6.2025  
