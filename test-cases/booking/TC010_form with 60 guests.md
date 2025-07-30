### Test Case ID: TC010  
**Target Description**: Attempt to submit reservation form with 60 guests  
**Suite**: Booking  
**Type**: Boundary / Functional  
**Priority**: Medium  
---

#### Pre-conditions:
1. User is on the homepage: https://simply33food.com/en  
2. Reservation form is visible and active  

---

#### Steps to Execute:

| Step | Action | Expected Result | Result | Bug Report ID |
|------|--------|------------------|--------|----------------|
| 1 | Click the "Reserve Now" button | The page scrolls smoothly to the reservation section located on the same page | ✅ | |
| 2 | Input the following data into the reservation form:<br>• Name: "Petro"<br>• Email: "petroshutiak@gmail.com"<br>• Branch: "Pizza Grill House"<br>• Phone: "+420770601299"<br>• Date: valid future date<br>• Time: available time<br>• Guests: 60 | If business rules allow such bookings, the input is accepted and no validation error appears. Otherwise, the "Guests" field is marked as invalid or a warning is displayed. | ❌ | <a href='https://github.com/shutiak/simply33-qa-portfolio/blob/main/bug-reports/bugs/bug14.md'>BUG-014</a> |
| 3 | Click the "Reserve" button | If accepted, a success message is displayed and reservation is submitted. If rejected, an error is shown explaining the guest limit. | ❌ | <a href='https://github.com/shutiak/simply33-qa-portfolio/blob/main/bug-reports/bugs/bug14.md'>BUG-014</a> |

---

**Executor**: Petro Shutiak  
**Date**: 4.6.2025  
