# Banus-Folder-Locker
Simple, secure folder locker for all your sensitive files. Completely local and nearly impossible to get past.  

---

I tried as much as I could to make sure that this program successfully encrypts and protects your sensitive files inside a folder vault using various security methods.

---

## Security Features

- ⚠️ **False-positive warning:**  
  Some antivirus programs may flag this tool as malware.  
  This is **only** because it uses encryption and anti-debugging techniques.  
  If this happens, simply add an antivirus exception for the folder you place it in.

The following security methods are used by this program:

- **Strong encryption:** Fernet (AES-256)  
- **Password protection:** Password is never stored in plaintext; only the hash is saved.  
- **Anti-debugging:** Detects and blocks attempts to tamper with or reverse engineer the program. 
- **Safe resets:** If you forget your password, the program can safely reset progress without leaving anything behind.  

---

## Extra Info

- You can type *"deletepassword"* into the password field to reset your progress if you forget it.  
  - **Warning:** Files that were encrypted will not be recoverable and will decrypt as garbage if you change the password.  
- This is X64 only. I'll make ARM64 in a minuteeeeeeeeeeeeeeeeeee
- DO NOT PUT YOUR FILES INSIDE OF THE LOCKFOLDER BEFORE YOU ADD A PASSWORD THAT SHIT IS GOING TO VANISH
- Contact me if you want like idk clarification that it's not malware or something. Discord is 'banus'
