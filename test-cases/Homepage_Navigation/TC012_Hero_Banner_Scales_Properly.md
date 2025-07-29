### Test Case ID: TC012  
**Target Description**: Verify that the hero banner image displays and scales correctly on various screen resolutions  
**Suite**: Homepage  
**Type**: UI / Responsive  
**Priority**: Medium  
---

#### Pre-conditions:
1. User has access to Chrome DevTools or physical devices  
2. Website is opened on the homepage: https://simply33food.com/en/  
3. The hero banner is the large image section at the top of the page  

---

#### Steps to Execute:

| Step | Action | Expected Result | Result | Bug Report ID |
|------|--------|------------------|--------|----------------|
| 1 | Open the homepage in desktop view (1920x1080) | Hero banner image is visible, clear, and scaled to fit the screen | ✅ |                |
| 2 | Resize the browser window to tablet view (820x1180) or simulate iPad Air | Image remains visible and adjusts without overlapping or breaking layout | ✅ |                |
| 3 | Resize or simulate mobile view (375x812) | Banner image adjusts responsively; buttons (if present) stay visible and usable | ✅ |                |
| 4 | Observe if any layout shift occurs when switching between resolutions | No image stretching, cutting, or unexpected layout shift should occur | ✅ |                |

---

**Executor**: Petro Shutiak  
**Date**: 22.7.2025
