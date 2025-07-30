# Pairwise Testing Checklist – Reservation Form (Desktop & Mobile)

This checklist covers reservation form behavior across key device/browser combinations using pairwise testing.

## Test Scope:
- Validate that the form functions correctly on different platforms
- Focus: layout, form visibility, field accessibility, successful submission, email confirmation

---

## Test Combinations

| # | Device      | Browser | Scenario                                                                 | Status | Bug Report ID | Notes                           |
|---|-------------|---------|--------------------------------------------------------------------------|--------|----------------|----------------------------------|
| 1 | Laptop      | Chrome  | Fill valid data → Submit form → Check confirmation and email             |❌    |<a href='https://github.com/shutiak/simply33-qa-portfolio/blob/main/bug-reports/bugs/bug14.md#bug-014-reservation-form-does-not-confirm-submission-after-entering-valid-data-and-clicking-reserve'>BUG-014</a>                |                    |
| 2 | Laptop      | Edge    | Fill valid data → Submit form → Check confirmation and email             |❌   |<a href='https://github.com/shutiak/simply33-qa-portfolio/blob/main/bug-reports/bugs/bug14.md#bug-014-reservation-form-does-not-confirm-submission-after-entering-valid-data-and-clicking-reserve'>BUG-014</a>         |     |
| 3 | iPad 10.2   | Chrome  | Landscape view → Fill valid data → Submit form                           |❌   <a href='https://github.com/shutiak/simply33-qa-portfolio/blob/main/bug-reports/bugs/bug14.md#bug-014-reservation-form-does-not-confirm-submission-after-entering-valid-data-and-clicking-reserve'>BUG-014</a>|                |     |
| 4 | iPhone 14   | Edge    | Mobile view → Fill form → Submit → Check layout and response             |❌  |<a href='https://github.com/shutiak/simply33-qa-portfolio/blob/main/bug-reports/bugs/bug14.md#bug-014-reservation-form-does-not-confirm-submission-after-entering-valid-data-and-clicking-reserve'>BUG-014</a>         |  |

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
