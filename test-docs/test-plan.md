# Test Plan – Simply33Food Website

## 1. Project Overview
This test plan describes the manual QA activities for the Simply33Food website – a real-world pizza restaurant platform that allows users to:
- Browse menu
- Order food online
- Reserve a table
- Register and log in
- Switch between Czech and English languages

URL: [https://simply33food.com/en/](https://simply33food.com/en/)

---

## 2. Objectives
- Validate the core functionality of the website
- Ensure proper display and behavior on different devices and browsers
- Identify UI/UX issues
- Test language localization
- Evaluate website responsiveness and load performance

---

## 3. Scope of Testing

### In Scope:
- Menu browsing
- Cart functionality
- Order placement flow
- Table reservation
- User registration & login
- UI elements (buttons, links, forms)
- Mobile/tablet responsiveness
- Language switch (EN/CZ)
- Browser compatibility (Chrome, Edge, Safari)
- Basic performance (load times)

### Out of Scope:
- Backend/database testing
- Payment gateway integration
- Admin panel (if exists and not publicly accessible)

---

## 4. Test Types
- Functional Testing
- UI/UX Testing
- Smoke Testing
- Regression Testing (if retesting bugs)
- Localization Testing (Czech & English)
- Compatibility Testing (browsers/devices)
- Usability Testing
- Responsive Design Testing
- (Optionally) API Testing via Postman

---

## 5. Test Approach

- Manual test cases will be created and executed
- AI tools may assist with test case drafting
- Bug reports will be created for each major issue found
- DevTools and Postman will be used where applicable

---

## 6. Test Environment

| Device Type | OS / Resolution           | Browsers       |
|-------------|---------------------------|----------------|
| Laptop      | Windows 11 / 1920×1080    | Chrome, Edge   |
| Mobile      | iOS / Android             | Safari, Chrome |
| Tablet      | iPad / Android Tablet     | Safari, Chrome |

---

## 7. Tools to Be Used

- **Test case design**: Markdown (.md), GitHub
- **Bug reporting**: Markdown bug templates
- **Performance**: Chrome DevTools → Lighthouse
- **API (if any)**: Postman (optional)

---

## 8. Entry Criteria

- Website is publicly accessible and stable
- Main functionalities are live
- Internet connection is stable

---

## 9. Exit Criteria

- All high-priority test cases executed
- No critical/high severity bugs remain open
- Test summary report completed

---

## 10. Deliverables

- `test-cases/`: Functional, UI, Localization test cases
- `bug-reports/`: Bug reports with screenshots
- `checklists/`: Smoke and regression checklists
- `test-docs/test-summary.md`: Final report with findings

---

## 11. Schedule

- Start Date: TBD
- Duration: Flexible (approx. 1–2 weeks part-time)

---

## 12. Tester Information

- **Name**: Petro Shutiak  
- **Role**: Independent QA Engineer  
- **Mode**: Manual testing only  


