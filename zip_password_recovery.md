

---

## 🔑 Stage 1: Cracking ZIP Password  

Note: Once these commands are run in a controlled lab environment, the tool will process the ZIP hash and display the recovered password.
This should only be done on your own test files for educational purposes.


We begin with `secret.zip` which is locked with a password.  
To extract the hash and recover the password:  


💡 After successful recovery:
The ZIP file is unlocked, and inside it we find another file: mi5hal.pdf, which is also password-protected.
This leads to Stage 2, where we recover the PDF password in the next step.

```bash
zip2john secret.zip > hash.txt
john hash.txt

