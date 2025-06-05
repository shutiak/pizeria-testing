### Test Case ID: TC001  
**Target Description**: Submit a reservation form with valid information  
**Suite**: Booking  
**Type**: Functional  
**Priority**: High  
---

#### Pre-conditions:
1. User is on the homepage: https://simply33food.com/  
2. Reservation form is visible and active  

---

#### Steps to Execute:

| Step | Action | Expected Result | Pass | Fail | Bug Report ID |
|------|--------|------------------|------|------|----------------|
| 1 | Input the following valid data into the reservation form:<br>• Name: "Petro"<br>• Email: "petroshutiak@gmail.com"<br>• Branch: "Pizza Grill House"<br>• Phone: "+420770601299"<br>• Date: any future date<br>• Time: available time<br>• Guests: 4<br>• Note: "birthday party" | All fields accept the input without displaying validation errors | | | |
| 2 | Click the "Reserve" button | A success message is displayed confirming that the reservation was submitted | | | |

---

#### Test Data:

- **Name**: Petro  
- **Email**: petroshutiak@gmail.com  
- **Branch**: Pizza Grill House  
- **Phone**: +420770601299  
- **Date**: (select a future date)  
- **Time**: (select a valid available time)  
- **Guests**: 4  
- **Note**: birthday party  

---

**Executor**: Petro Shutiak  
**Date**: 4.6.2025  
