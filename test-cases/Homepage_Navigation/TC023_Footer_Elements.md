### Test Case ID: TC023  
**Target Description**: Verify that all links and buttons in the footer are functional and redirect to the correct pages  
**Suite**: Homepage_Footer  
**Type**: Functional  
**Priority**: Medium  

---

#### Pre-conditions:
1. User is on the homepage: https://simply33food.com/en/  
2. Footer is fully loaded and visible  

---

#### Steps to Execute:

| Step | Action | Expected Result | Result | Bug Report ID |
|------|--------|------------------|--------|----------------|
| 1 | Scroll to the bottom of the homepage | Footer becomes visible | ✅ |                |
| 2 | Click on the “View larger map” in the Google map | Google Maps opens in a new tab with location of Simply 33 | ✅ |                |
| 3 | Click on "CAREERS" link | Redirects to careers page | ✅ |                |
| 4 | Click on "OBCHODNÍ PODMÍNKY" link | Opens Terms and Conditions page in correct language | ❌ | <a href='https://github.com/shutiak/simply33-qa-portfolio/blob/main/bug-reports/bugs/bug10.md#bug-010-terms-and-conditions-link-on-english-version-leads-to-czech-content'>BUG-010</a>        |
| 5 | Click on "COOKIES" link | Opens Cookies policy page in correct language | ❌ | <a href='https://github.com/shutiak/simply33-qa-portfolio/blob/main/bug-reports/bugs/bug11.md#bug-011-cookies-page-on-english-version-contains-czech-content'>BUG-011</a>        |
| 6 | Click on "Payment methods info" | Redirects to page with info about payment methods | ✅ |                |
| 7 | Click Facebook icon | Opens correct Simply 33 Facebook page in new tab | ✅ |                |
| 8 | Click Instagram icon | Opens correct Simply 33 Instagram page in new tab | ❌ | <a href='https://github.com/shutiak/simply33-qa-portfolio/blob/main/bug-reports/bugs/bug7.md#bug-007-reserve-now-and-order-online-buttons-shift-below-hero-banner-on-ipad-air-820x1180'>BUG-007</a>        |
| 9 | Click X (Twitter) icon | Opens correct Twitter/X page in new tab | ✅ |                |
| 10 | Hover over the black "Want a Discount?" button | Text becomes visible and confirms the button is interactive | ❌ | <a href='https://github.com/shutiak/simply33-qa-portfolio/blob/main/bug-reports/bugs/bug9.md#bug-009-text-on-black-button-in-footer-not-visible-until-hovered'>BUG-009</a>        |
| 11 | Click on SIMPLY 33 Cinema & Karaoke Bar logo | Opens correct partner site in new tab | ✅ |                |

---

**Executor**: Petro Shutiak  
**Date**: 30.7.2025  
