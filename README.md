# 🔐 Ethical Hacking: Password Cracking Labs  

This repository showcases my **ethical hacking practice** in password recovery using open-source tools.  
The focus is on **multi-layer password cracking**: a password-protected ZIP file that contains a second protected PDF.  

💡 This project is purely for **educational purposes** on my **own test files** in a controlled lab environment.  

---

## 📂 Workflow Overview  

1. 🗂️ Start with a password-protected `secret.zip`.  
2. 🔑 Use `zip2john` + `john` to recover the ZIP password.  
3. 📑 Inside the ZIP is another protected file: `mi5hal.pdf`.  
4. 🧩 Use `pdfcrack` to recover the PDF password.  
5. 🎯 Access the original data successfully.  

---

## ⚙️ Tools Used  

- [John the Ripper](https://www.openwall.com/john/) – ZIP password recovery  
- [fcrackzip](https://manpages.debian.org/fcrackzip) – alternative ZIP cracking  
- [pdfcrack](http://pdfcrack.sourceforge.net/) – PDF password recovery  

---

## 🗂️ Repository Structure  

