### Test Case ID: TC016  
**Target Description**: Verify that the selected language remains active after reloading the page  
**Suite**: Localization  
**Type**: Functional / Localization  
**Priority**: Medium  
---

#### Pre-conditions:
1. User is on the homepage: https://simply33food.com/en/  
2. Language switcher is visible  
3. Browser cookies or local storage are enabled (default settings)  

---

#### Steps to Execute:

| Step | Action | Expected Result | Result | Bug Report ID |
|------|--------|------------------|--------|----------------|
| 1 | On the homepage, click the language switcher and select "CZ" | Page reloads or redirects to `/cz/` version | ⬜ |                |
| 2 | Press Ctrl+R or click the browser reload button | The page reloads but stays in the Czech version (`/cz/`) | ⬜ |                |
| 3 | Close the browser tab, open a new tab, and manually enter https://simply33food.com | Website opens in Czech version if language is stored | ⬜ |                |
| 4 | Repeat the same steps using English version (`/en/`) | Site stays in English after reload or revisit | ⬜ |                |

---

**Executor**: Petro Shutiak  
**Date**: 22.7.2025

