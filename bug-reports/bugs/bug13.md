# BUG-013: Site Defaults to Czech Language on Revisit Even After Selecting English

**Environment:**
- Device: Windows 11  
- Browser: Chrome 138.0  
- URL: https://simply33food.com  
- Language Selected: EN  

---

### Preconditions:
- User has previously selected **English** (`/en/`) as the preferred language using the language switcher  
- Browser cookies and local storage are enabled (default behavior)

---

### Steps to Reproduce:
1. Open `https://simply33food.com/en/`  
2. Close the tab or browser  
3. Open a new browser tab and enter `https://simply33food.com` manually  
4. Observe the language of the landing page

---

### Actual Result:
- The site **defaults back to Czech** (`/cz/`) despite the user having previously selected the English version.

### Expected Result:
- The site should **remember the user’s language preference** and load the English version (`/en/`) if it was the last selected language.

---

**Severity:** Medium  
**Priority:** Medium 
