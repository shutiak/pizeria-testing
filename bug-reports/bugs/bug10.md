# BUG-010: "Terms and Conditions" Link on English Version Leads to Czech Content

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
2. Click on the link labeled **"obchodní podmínky"**  
3. Observe the content of the loaded page

---

### Actual Result:
- The link opens the page `https://simply33food.com/en/obchodni-podminky/`, but the content is in **Czech** despite being under the English `/en/` path.

### Expected Result:
- The page `https://simply33food.com/en/obchodni-podminky/` should display content in **English**, titled "Terms and Conditions".

---

**Severity:** Minor  
**Priority:** Low


**Attachments:** <br>
<img width="956" height="473" alt="image" src="https://github.com/user-attachments/assets/a61cd632-dd28-4261-bcad-b9a265b848c7" />



