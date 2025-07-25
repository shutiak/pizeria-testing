# BUG-004: Meta tags (title and description) remain in English after switching to Czech

**Environment:**
- Device: Windows 11
- Browser: Chrome 138.0
- URL: https://simply33food.com/cz/

**Preconditions:**
- User opens `https://simply33food.com/en/`
- Chrome DevTools is open, with the "Elements" tab selected

**Steps to Reproduce:**
1. Inspect the `<title>`, `<meta property="og:title"> and `<meta property="og:description">` tags in the `<head>` section
2. Switch the website language from English to Czech using the language switcher
3. Navigate to `https://simply33food.com/cz/`
4. Inspect the same meta tags again in Chrome DevTools

**Actual Result:**
- The content of the `<title>`, `<meta property="og:title"> and `<meta property="og:description">` remains in English on the Czech version of the website

**Expected Result:**
- The meta tags should be localized and displayed in Czech on the Czech version of the website

**Severity:** Minor  
**Priority:** Low

**Attachments:**
<img width="707" height="151" alt="image" src="https://github.com/user-attachments/assets/689078f4-b94a-4eb3-a317-3d8d42a24e14" />
