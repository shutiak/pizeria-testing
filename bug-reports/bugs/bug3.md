# BUG-003: Largest Contentful Paint exceeds 8s on homepage (Lighthouse audit)

**Environment:**
- Device: Windows 11
- Browser: Chrome 138.0
- URL: https://simply33food.com/en/
- Tool: Google Lighthouse (Performance audit)
- Network: Simulated Fast 3G

**Preconditions:**
- User opens Chrome DevTools
- Runs Lighthouse audit in Performance mode

**Steps to Reproduce:**
1. Open `https://simply33food.com/en/`
2. Open Chrome DevTools → Lighthouse tab
3. Select "Performance" and run the audit
4. Observe the metric: Largest Contentful Paint (LCP)

**Actual Result:**
- Largest Contentful Paint: **8.1 seconds**
- Speed Index: **2.8 seconds**
- Total Blocking Time: 190 ms
- Cumulative Layout Shift: 0.007

**Expected Result:**
- Largest Contentful Paint should be **under 2.5 seconds**
- Overall page should be fully interactive in under 3 seconds

**Severity:** Medium  
**Priority:** High

**Attachments:**
<img width="959" height="484" alt="image" src="https://github.com/user-attachments/assets/01b2ac5e-2706-45cf-8ba3-ae0c10526101" />



