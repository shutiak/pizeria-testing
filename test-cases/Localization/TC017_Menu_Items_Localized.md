### Test Case ID: TC017  
**Target Description**: Verify that menu item names and descriptions are properly localized when switching language  
**Suite**: Localization  
**Type**: Functional / Localization / UI  
**Priority**: High  
---

#### Pre-conditions:
1. User is on the homepage: https://simply33food.com/en/  
2. Menu section is available and visible  
3. Language switcher is accessible in the header  

---

#### Steps to Execute:

| Step | Action | Expected Result | Result | Bug Report ID |
|------|--------|------------------|--------|----------------|
| 1 | Scroll to the menu section while in English version (`/en/`) | All menu item titles and descriptions are in English | ✅ |                |
| 2 | Note the name and description of 2–3 sample dishes | Text is clear and grammatically correct | ✅ |                |
| 3 | Use the language switcher to change to Czech | Page reloads or redirects to `/cz/` | ✅ |                |
| 4 | Scroll to the same menu items in Czech version | Titles and descriptions are shown in Czech | ✅ |                |
| 5 | Verify that no English text appears on Czech version | All visible content matches selected language | ✅ |                |

---

**Executor**: Petro Shutiak  
**Date**: 22.7.2025
