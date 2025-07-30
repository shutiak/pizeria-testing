# BUG-014: Reservation form does not confirm submission after entering valid data and clicking "Reserve"

**Environment:**
- Device: Windows 11  
- Browser: Chrome 138.0  
- URL: https://simply33food.com/en/  
- Language: EN  

---

**Preconditions:**
- User is on the homepage in English version (`/en/`)  
- The "Reserve Now" button and reservation form are visible  

---

**Steps to Reproduce:**
1. On the homepage, click the **"Reserve Now"** button  
2. Fill in the reservation form with the following valid data:  
   - Name: `Petro`  
   - Email: `petroshutiak@gmail.com`  
   - Branch: `Pizza Grill House`  
   - Phone: `+420770601299`  
   - Date: any future date  
   - Time: available time  
   - Guests: `4`  
   - Note: `birthday party`  
3. Click the **"Reserve"** button  

---

**Actual Result:**  
- The loading spinner appears after clicking the "Reserve" button, but no success message or error message is displayed.  
- The user remains on the same section with no confirmation of submission.

**Expected Result:**  
- A visible success message should appear, confirming that the reservation was submitted successfully.  
- Alternatively, a clear error message should be shown if something went wrong.

---

**Severity:** Critical  
**Priority:** High

**Attachments:** <br><img width="956" height="472" alt="image" src="https://github.com/user-attachments/assets/5e9e7a9c-58c8-4625-ac8c-db3a624a3fda" />

