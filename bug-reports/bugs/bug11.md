# BUG-011: "Cookies" Page on English Version Contains Czech Content

**Environment:**
- Device: Windows 11  
- Browser: Chrome 138.0  
- URL: https://simply33food.com/en/  
- Language: EN  

---

### Preconditions:
- User is on the homepage in English version (`/en/`)  
- User has scrolled to the footer

---

### Steps to Reproduce:
1. Locate the **"Important Links"** section in the footer  
2. Click on the link labeled **"Cookies"**  
3. Observe the content of the loaded page: `https://simply33food.com/en/cookies/`

---

### Actual Result:
- The page `https://simply33food.com/en/cookies/` opens, but the content is written in **Czech**.

### Expected Result:
- The page should display **English-language** content about cookie usage, since the user is browsing the English version of the site.

---

**Severity:** Minor  
**Priority:** Low

**Attachments:** <br> <img width="956" height="478" alt="image" src="https://github.com/user-attachments/assets/11a6cfc6-8871-4cb8-aab3-3e697ada4187" />
