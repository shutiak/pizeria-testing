### Test Case ID: TC009  
**Target Description**: Verify that a confirmation email is sent after successful reservation submission  
**Suite**: Booking  
**Type**: Functional / Communication  
**Priority**: High  
---

#### Pre-conditions:
1. User is on the homepage: https://simply33food.com/en  
2. Reservation form is visible and active  
3. The form is already filled in with valid data:<br>• Name: "Petro"<br>• Email: "petroshutiak@gmail.com"<br>• Branch: "Pizza Grill House"<br>• Phone: "+420770601299"<br>• Date: valid future date<br>• Time: available time<br>• Guests: 4

---

#### Steps to Execute:

| Step | Action | Expected Result | Result | Bug Report ID |
|------|--------|------------------|--------|----------------|
| 1 | Click the "Reserve" button | A success message is displayed confirming that the reservation was submitted | ❌ | <a href='https://github.com/shutiak/simply33-qa-portfolio/blob/main/bug-reports/bugs/bug14.md'>BUG-014</a> |
| 2 | Open the inbox of the provided email address | A confirmation email is received within 5 minutes containing the reservation details | ❌ | <a href='https://github.com/shutiak/simply33-qa-portfolio/blob/main/bug-reports/bugs/bug14.md'>BUG-014</a> |

---

**Executor**: Petro Shutiak  
**Date**: 4.6.2025  
