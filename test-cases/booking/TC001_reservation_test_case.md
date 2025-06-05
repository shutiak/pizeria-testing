---

### ✅ Test Case ID: TC001  
**Target Description**: Booking with valid information in the reservation form  
**Suite**: Booking  
**Type**: Functional  
**Priority**: High  

---

#### 🔒 Pre-conditions:
1. User is on the homepage: https://simply33food.com/  
2. Reservation form is visible and active  

---

#### 📋 Steps to Execute:

| Step | Action                                                                                                   | Expected Result                                                                                   | Pass | Fail | Bug Report ID |
|------|----------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------|------|------|----------------|
| 1    | Input valid data:  
- Name: "Petro"  
- Email: "petroshutiak@gmail.com"  
- Branch: "Pizza Grill House"  
- Phone: "+420770601299"  
- Date: any future date  
- Time: available time  
- Guests: 4  
- Note: "birthday party" | All input fields accept the values without showing any validation error                            |      |      |                |
| 2    | Click the "Reserve" button                                                                               | A success message is displayed confirming the reservation submission                              |      |      |                |

---

**Executor**: Petro Shutiak  
**Date**: 4.6.2025  
