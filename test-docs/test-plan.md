# Test Plan — Simply33 Website

## 1. Objective

To evaluate the functionality, usability, responsiveness, localization, and performance of the Simply33 restaurant website.

## 2. Scope of Testing

### In-Scope:
- Public web pages (EN/CZ)
- Food menu listings
- Ordering button behavior (redirect/iframe)
- Language switcher
- Contact information
- Mobile/Tablet/Desktop responsiveness

### Out-of-Scope:
- Backend or admin panel (not accessible)
- Internal order processing logic (handled by external iframe)
- Payment system (handled by third party)

## 3. Types of Testing

- Functional Testing
- UI/UX Testing
- Localization Testing
- Compatibility Testing (Browsers & Devices)
- Responsive Design Testing
- Exploratory Testing
- Accessibility (basic WCAG checks)
- Performance (using Google Lighthouse)

## 4. Tools

- Browser DevTools (Chrome)
- Postman (for external API tests if needed)
- GitHub (documentation)
- Google Lighthouse
- Screenshots / Screen recordings

## 5. Deliverables

- Checklists
- Test Cases
- Bug Reports
- Screenshots
- Test Summary Report (final stage)

## 6. Test Environments

- OS: Windows 11, Android 11, iOS 18
- Browsers: Chrome, Firefox, Safari (Mobile)
- Resolutions: 1920x1080, 768x1024, 375x812

## 7. Risks & Limitations

- External iframe (ordering system) is out of our control
- No access to internal analytics or CMS
- Limited info about expected behavior (no formal requirements)
