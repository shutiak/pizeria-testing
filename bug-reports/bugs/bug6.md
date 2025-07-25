# BUG-006: Order form is missing on pizza offer pages

**Description:**
On the pages for special promotional offers — “Pizza offer: 1 + 1 = Margherita” and “Veggie pizza offer: 1 + 1 = Margherita” — the order form is missing. The form appears only in a modal window when the user clicks "Add to cart", but is not visible directly on the offer pages.

**Environment:**
- Device: Windows 11
- Browser: Chrome 138.0
- URL: https://simply33food.com/en/
- Language: EN

**Preconditions:**
- User is on the English homepage (`/en/`)

**Steps to Reproduce:**
1. Click on the title or image of the offer:
   - "Pizza offer: 1 + 1 = Margherita"
   - "Veggie pizza offer: 1 + 1 = Margherita"
2. Observe the loaded page

**Actual Result:**
- No visible order form is displayed on the offer page.
- The user can only place an order via a modal window after clicking "Add to cart" from the main menu.

**Expected Result:**
- Each pizza offer page should display a clearly visible order form or embedded ordering section for the promoted item.

**Severity:** Medium  
**Priority:** Medium

**Attachments:**
<img width="959" height="538" alt="image" src="https://github.com/user-attachments/assets/c51a3e0b-def8-4dde-9217-db49f7a30c42" />



