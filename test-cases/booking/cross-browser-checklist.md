# Pairwise Testing Checklist – Reservation Form (Desktop & Mobile)

This checklist covers reservation form behavior across key device/browser combinations using pairwise testing.

## Test Scope:
- Validate that the form functions correctly on different platforms
- Focus: layout, form visibility, field accessibility, successful submission, email confirmation

---

## Test Combinations

| # | Device      | Browser | Scenario                                                                 | Status | Bug Report ID | Notes                           |
|---|-------------|---------|--------------------------------------------------------------------------|--------|----------------|----------------------------------|
| 1 | Laptop      | Chrome  | Fill valid data → Submit form → Check confirmation and email             |    |                |                    |
| 2 | Laptop      | Edge    | Fill valid data → Submit form → Check confirmation and email             |   |         |     |
| 3 | iPad 10.2   | Chrome  | Landscape view → Fill valid data → Submit form                           |    |                |     |
| 4 | iPhone 14   | Edge    | Mobile view → Fill form → Submit → Check layout and response             |   |         |  |

---

## Notes:
- Use the following input data across all tests:
  - Name: Petro
  - Email: petroshutiak@gmail.com
  - Phone: +420770601299
  - Branch: Pizza Grill House
  - Date: any valid future date
  - Time: available time
  - Guests: 4

- Validation and email delivery must be tested where possible.

---

**Created by**: Petro Shutiak  
**Date**: 4 June 2025
