# 🔐 RA-1 | ZIP Password Brute Force Unlocker

**RA-1**, is a lightweight but savage batch script designed to unlock password-protected `.zip` files using brute-force attacks.

> **⚠️ Ethical Notice:** This tool is made for recovering YOUR OWN protected files or for educational purposes in cybersecurity. Misuse for unauthorized access is strictly illegal.

---

## 🚀 Features
- **Brute Force Attack**: Attempts every password from a user-provided wordlist.
- **Simple Setup**: Pure batch scripting. No crazy installs. No bloated dependencies.
- **Lightweight**: < 10KB footprint.
- **Educational**: Great for learning how basic brute force techniques work.

---

## 🔧 How It Works
1. You provide:
   - Path to the locked `.zip` file.
   - Path to a password wordlist (`.txt` file with one password per line).
2. RA-1 loops through each password and tries to extract the zip.
3. If successful, it immediately stops and tells you the correct password.

---

## 📝 Usage

### 1. Requirements
- Windows OS (Batch files are native)
- [7-zip](https://www.7-zip.org/) software should install
- A `.zip` archive you have permission to unlock
- A wordlist of possible passwords ( you can use [CRUNCH](https://sourceforge.net/projects/crunch-wordlist/) tool to generate wordlist )

### 2. Running the Tool
```bash
Simply double-click `RA-1.bat` OR run it from Command Prompt:

> RA-1.bat
```

Follow the prompts:
- Enter the full path to your `.zip` file.
- Enter the full path to your password list.

The script will start hammering the zip until it cracks or exhausts the list.

---

## 🔍 Example
```plaintext
Enter path to ZIP file: C:\Users\You\Desktop\locked.zip
Enter path to wordlist: C:\Users\You\Desktop\rockyou.txt
```
Then watch it GO BRRRRRR...

---

## 🤖 Tips for Better Success
- Use curated or massive password lists like `rockyou.txt`, `darkc0de.txt`, or custom ones.
- Target likely passwords first (birthday years, common words, etc).
- Passwords with crazy symbols and length >10 chars will take longer.
  
---

## REMEMBER

if a password have 5 character with combination of (0-9),(A-Z),(a-z),

So total possible characters = ``10 + 26 + 26 = 62 characters``

Now, since each of the 5 characters can be any of the 62,
the total number of possible passwords is:

62<sup>5</sup> = **916,132,832**

😂 just think about 8 character password

---

## 🔐 Legal Stuff
This project is made with ❤️ for cybersecurity learning.

**Do not** use this on files you do not own or have explicit permission to test.

You are 100% responsible for your own actions.

---

## 🔗 Connect With Me
**Author**: ASKI001

If you liked this project, drop a star ⭐ and let's make hacking ethical, powerful, and badass.

---


