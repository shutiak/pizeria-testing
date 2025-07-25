# BUG-007: "Reserve Now" and "Order Online" buttons shift below hero banner on iPad Air (820x1180)

**Environment:**
- Device: iPad Air (820px x 1180px)
- OS: iOS 18.5
- Browser: Safari (default)
- URL: https://simply33food.com/en/
- Language: EN

**Preconditions:**
- User opens the homepage in English (`/en/`)
- Viewport resolution is set to iPad Air dimensions (820x1180)

**Steps to Reproduce:**
1. Open the homepage on an iPad Air (or simulate the resolution in Chrome DevTools).
2. Locate the buttons "Reserve Now" and "Order Online" near the hero banner.
3. Observe their placement in relation to the banner image.

**Actual Result:**
- The buttons appear **below** the hero banner and are partially or fully overlapped by it.

**Expected Result:**
- The buttons should appear **on top of the banner**, aligned as in desktop and mobile views.

**Severity:** Minor  
**Priority:** Low

**Attachments:** <br>
<img width="250" height="278" alt="image" src="https://github.com/user-attachments/assets/fecba68f-18d0-4e29-bf28-09c3570ca59f" />


