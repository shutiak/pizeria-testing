### Test Case ID: TC013  
**Target Description**: Verify that "Reserve Now" and "Order Online" buttons are visible and clickable across screen sizes  
**Suite**: Homepage  
**Type**: Functional / UI / Responsive  
**Priority**: High  
---

#### Pre-conditions:
1. User is on the homepage: https://simply33food.com/en/  
2. Buttons "Reserve Now" and "Order Online" are located near the top hero banner  
3. Test is performed on desktop, tablet (iPad Air 820x1180), and mobile (375x812)  

---

#### Steps to Execute:

| Step | Action | Expected Result | Result | Bug Report ID |
|------|--------|------------------|--------|----------------|
| 1 | Open the homepage in desktop view | Both buttons are clearly visible and placed above the hero image | ✅ |                |
| 2 | Resize to iPad Air resolution (820x1180) or simulate in DevTools | Buttons remain visible and do not shift below the banner | ❌ | BUG-007         |
| 3 | Resize to mobile resolution (375x812) or use a physical mobile device | Buttons are either visible or accessible through scrolling/tap | ✅ |                |
| 4 | Click the "Reserve Now" button | Page scrolls to the reservation section | ✅ |                |
| 5 | Click the "Order Online" button | External ordering iframe opens or scrolls to the order section | ✅ |                |

---

**Executor**: Petro Shutiak  
**Date**: 22.7.2025
