### Test Case ID: TC018  
**Target Description**: Verify that all footer elements (text, labels, links) are properly localized when switching the site language  
**Suite**: Localization  
**Type**: Functional / Localization / UI  
**Priority**: Medium  
---

#### Pre-conditions:
1. User is on the homepage: https://simply33food.com/en/  
2. Footer is visible at the bottom of the page  
3. Language switcher is accessible in the header  

---

#### Steps to Execute:

| Step | Action | Expected Result | Result | Bug Report ID |
|------|--------|------------------|--------|----------------|
| 1 | Scroll to the footer in the English version (`/en/`) | All text in the footer (e.g. labels, section names) is in English | ⬜ |                |
| 2 | Observe contact info, legal links, and any service descriptions | No text appears in Czech or mixed language | ⬜ |                |
| 3 | Switch language to Czech using the language switcher | Page reloads or redirects to `/cz/` | ⬜ |                |
| 4 | Scroll to the footer again and observe all textual content | Footer content is now displayed in Czech | ⬜ |                |
| 5 | Confirm that no English words remain (unless proper nouns) | Footer is fully localized to Czech | ⬜ |                |

---

**Executor**: Petro Shutiak  
**Date**: 22.7.2025
