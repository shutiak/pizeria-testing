### Test Case ID: TC015  
**Target Description**: Verify that switching the language using the language switcher changes the visible content on the homepage  
**Suite**: Localization  
**Type**: Functional / UI / Localization  
**Priority**: High  
---

#### Pre-conditions:
1. User is on the homepage: https://simply33food.com/en/  
2. Language switcher is visible (usually in the header or top-right corner)  
3. Both English and Czech versions are implemented and functional  

---

#### Steps to Execute:

| Step | Action | Expected Result | Result | Bug Report ID |
|------|--------|------------------|--------|----------------|
| 1 | Observe the current language (EN) and some sample content (e.g. CTA button, menu title) | All text is in English | ⬜ |                |
| 2 | Click the language switcher and select "CZ" | Page reloads or updates to the Czech version (`/cz/`) | ⬜ |                |
| 3 | Verify that visible content is now in Czech (e.g. buttons, menu section, headings) | All major interface elements are translated to Czech | ⬜ |                |
| 4 | Switch back to English using the same switcher | Page reloads or updates to the English version (`/en/`) | ⬜ |                |
| 5 | Confirm that English content is restored correctly | All elements display text in English again | ⬜ |                |

---

**Executor**: Petro Shutiak  
**Date**: 22.7.2025
