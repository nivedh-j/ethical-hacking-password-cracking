

---

## 🔑 Stage 1: Cracking ZIP Password  

We begin with `secret.zip` which is locked with a password.  
To extract the hash and recover the password:  

```bash
zip2john secret.zip > hash.txt
john hash.txt


Note: Once these commands are run in a controlled lab environment, the tool will process the ZIP hash and display the recovered password.
This should only be done on your own test files for educational purposes.
