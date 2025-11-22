# Banus-Folder-Locker
Simple, secure folder locker for all your sensitive files. Completely local and nearly impossible to get past.  

---

I tried as much as I could to make sure that this program successfully encrypts and protects your sensitive files inside a folder vault using various security methods.

---

## Security Features

The following security methods are used by this program:

- **Strong encryption:** Fernet (AES-256)  
- **Password protection:** Password is never stored in plaintext; only the hash is saved.  
- **Anti-debugging:** Detects and blocks attempts to tamper with or reverse engineer the program.  
- **Safe resets:** If you forget your password, the program can safely reset progress without leaving anything behind.  

---

## Extra Info

- You can type *"deletepassword"* into the password field to reset your progress if you forget it.  
  - **Warning:** Files that were encrypted will not be recoverable and will decrypt as garbage if you change the password.  
