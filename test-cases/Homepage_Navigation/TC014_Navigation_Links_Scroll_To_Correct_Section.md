### Test Case ID: TC014  
**Target Description**: Verify that top navigation links and dropdown items redirect to the correct pages and appear on hover  
**Suite**: Homepage_Navigation  
**Type**: Functional / UI  
**Priority**: High  
---

#### Pre-conditions:
1. User is on the homepage: https://simply33food.com/en/  
2. Top navigation bar is fully loaded and visible  
3. Device: Desktop view (≥ 1024px) — hover behavior applies  

---

#### Steps to Execute:

| Step | Action | Expected Result | Result | Bug Report ID |
|------|--------|------------------|--------|----------------|
| 1 | Click on the "Menu" link in the top navigation | User is redirected to: `https://simply33food.com/en/menu/` | ✅ |                |
| 2 | Click on the "About Us" link in the top navigation | User is redirected to: `https://simply33food.com/en/about-us/` | ✅ |                |
| 3 | Click on the "Log In" link in the top navigation | User is redirected to: `https://simply33food.com/en/my-account/` | ✅ |                |
| 4 | Hover over the "Menu" navigation item | A dropdown appears with: "Special Offers", "Alcohol Sets" | ✅ |                |
| 5 | Hover over the "About Us" navigation item | A dropdown appears with: "Gallery" | ✅ |                |
| 6 | Click on "Special Offers" from the dropdown | User is redirected to: `https://simply33food.com/en/special-offers/` | ✅ |                |
| 7 | Click on "Alcohol Sets" from the dropdown | User is redirected to: `https://simply33food.com/en/menu/#alcohol-sets` | ❌ |<a href="https://github.com/shutiak/simply33-qa-portfolio/blob/main/bug-reports/bugs/bug1.md#bug-001-alcohol-sets-navigation-link-redirects-to-czech-version-instead-of-english">BUG-001</a>                |
| 8 | Click on "Gallery" from the dropdown | User is redirected to: `https://simply33food.com/en/gallery/` | ✅ |                |

---

**Executor**: Petro Shutiak  
**Date**: 22.7.2025
