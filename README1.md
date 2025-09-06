

---

## 🔑 Stage 1: Cracking ZIP Password  

We begin with `secret.zip` which is locked with a password.  
To extract the hash and recover the password:  

```bash
zip2john secret.zip > hash.txt
john hash.txt
