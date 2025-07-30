# BUG-014: Reservation form is completely non-functional — no confirmation, no validation errors, no user feedback

**Environment:**
- Device: Windows 11
- Browser: Chrome 138.0
- URL: https://simply33food.com/en/
- Language: EN

---

### **Preconditions:**
- User is on the homepage in English version (`/en/`)
- "Reserve Now" button is visible and leads to the reservation form section

---

### **Steps to Reproduce:**
1. Click the "Reserve Now" button
2. Fill in the reservation form with either:
   - Valid data:
     - Name: "Petro"
     - Email: "petroshutiak@gmail.com"
     - Branch: "Pizza Grill House"
     - Phone: "+420770601299"
     - Date: any future date
     - Time: available time
     - Guests: 4
     - Note: "birthday party"
   - Invalid data (for negative tests), such as:
     - Leaving required fields empty
     - Using invalid email format
     - Entering past dates or invalid characters
3. Click the **"Reserve"** button

---

### **Actual Result:**
- No success message, no validation errors
- Only a loading spinner appears briefly, then nothing happens
- User is left without any confirmation or instruction
- Issue occurs for both valid and invalid input

---

### **Expected Result:**
- For valid input: a success message confirms the reservation
- For invalid input: appropriate validation errors are shown next to incorrect or empty fields

---

### **Affected Test Cases:**
- TC001_form with valid information
- TC002_Form with an invalid name
- TC003_form with an invalid email
- TC004_form witn invalid phone
- TC005_form with a past date
- TC006_form with a time outside business hours
- TC007_form with number of guests set to 0
- TC008_form with number of guests set to -1
- TC009_confirmation email
- TC010_form with 60 guests
- cross-browser-checklist

---

**Severity:** Critical  
**Priority:** High  

**Reported by:** Petro Shutiak  
**Date:** 30.7.2025  


**Attachments:** <br><img width="956" height="472" alt="image" src="https://github.com/user-attachments/assets/5e9e7a9c-58c8-4625-ac8c-db3a624a3fda" />

