# BUG-014: Reservation form fails to submit across all tested devices and browsers

**Environment:**
- URL: https://simply33food.com/en/
- Language: EN
- Devices & Browsers:
  - Laptop / Chrome (Windows 11)
  - Laptop / Edge (Windows 11)
  - iPad 10.2 / Chrome (iOS)
  - iPhone 14 / Edge (iOS)

**Preconditions:**
- User is on the homepage in English version (`/en/`)
- The “Reserve Now” button is visible and functional
- All test cases use valid and complete input data

---

**Steps to Reproduce (for each configuration):**
1. Click the “Reserve Now” button on homepage
2. Fill out the reservation form with the following data:
   - Name: "Petro"
   - Email: "petroshutiak@gmail.com"
   - Branch: "Pizza Grill House"
   - Phone: "+420770601299"
   - Date: any future date
   - Time: any available time
   - Guests: 4
   - Note: "birthday party"
3. Click the “Reserve” button
4. Observe the result

---

**Actual Result:**

| # | Device      | Browser | Result |
|---|-------------|---------|--------|
| 1 | Laptop      | Chrome  | Loading icon appears but nothing happens |
| 2 | Laptop      | Edge    | Error message: `There was an error trying to send your message. Please try again later.` |
| 3 | iPad 10.2   | Chrome  | Error message: `There was an error trying to send your message. Please try again later.` |
| 4 | iPhone 14   | Edge    | Loading icon appears but nothing happens |

---

**Expected Result:**
- Form is submitted successfully and a success message is shown
- Confirmation email is sent to the user (optional but expected)

---

**Severity:** Critical  
**Priority:** Highest  

---

**Blocked Tests:**
Due to this bug, the following negative test cases could not be executed and are considered blocked:
- TC002_Form with an invalid name.md
- TC003_form with an invalid email.md
- TC004_form witn invalid phone.md
- TC005_form with a past date.md
- TC006_form with a time outside business hours.md
- TC007_form with number of guests set to 0.md
- TC008_form with number of guests set to -1.md
- TC009_confirmation email.md
- TC010_form with 60 guests.md


**Attachments:** <br> 
Laptop (Chrome): <br>
<img width="956" height="472" alt="image" src="https://github.com/user-attachments/assets/5e9e7a9c-58c8-4625-ac8c-db3a624a3fda" /> <br>
Laptop (Edge):<br> <img width="941" height="474" alt="image" src="https://github.com/user-attachments/assets/e1496b47-9a9a-4afe-a612-1258a84ceb52" /> <br>
IPad 10.2 (Chrome): <br><img width="640" height="480" alt="image" src="https://github.com/user-attachments/assets/eb5f600f-d0bb-4655-9995-7554ca764eef" /><br>
IPhone 14 (Edge): <br><img width="296" height="640" alt="image" src="https://github.com/user-attachments/assets/debc867e-b9b1-4543-89a1-8c4f25618de7" />



