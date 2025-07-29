# BUG-012: Notification Banner Remains in English After Switching to Czech Language

**Environment:**
- Device: Windows 11  
- Browser: Chrome 138.0  
- URL: https://simply33food.com/en/ → https://simply33food.com/cz/  
- Language: Initially EN, then switched to CZ  

---

### Preconditions:
- The restaurant is currently **closed** (outside of business hours)  
- User starts on the **English** version of the homepage (`/en/`)

---

### Steps to Reproduce:
1. Open `https://simply33food.com/en/` during closed hours  
2. Use the **language switcher** to change the site language to Czech (`/cz/`)  
3. Wait up to 10 seconds for the automatic banner informing users that the restaurant is closed  
4. Observe the **language** of the notification content

---

### Actual Result:
- Even after switching to Czech, the push notification banner is still shown in **English**, e.g.:  
  `"We are currently closed. Orders will not be processed until we open."`

### Expected Result:
- The banner message should reflect the **selected language** (Czech), e.g.:  
  `"Nyní máme zavřeno. Objednávky nebudou zpracovány, dokud znovu neotevřeme."`

---

**Severity:** Minor  
**Priority:** Medium  

**Attachments:** <br> <img width="944" height="469" alt="image" src="https://github.com/user-attachments/assets/7ce71922-25ae-45e1-ae15-b30d87e3501f" />

