# 🧑‍💻 Advanced Login System (Tkinter + SQLite + PIL)

## 📘 Overview

This project is a **secure login and registration system** built using **Python’s Tkinter GUI framework**, **SQLite database**, and **Pillow (PIL)** for background image handling.

It includes:

* Secure password hashing (SHA-256)
* Registration with email validation
* Login authentication
* Forgot password feature
* Dynamic backgrounds
* Basic password strength checking
* Simple dashboard after login

---

## ⚙️ Features

✅ **User Registration**

* Validates email format
* Checks password strength
* Prevents duplicate usernames

✅ **User Login**

* Authenticates username and password
* Uses SHA-256 hashing for secure storage

✅ **Forgot Password**

* Allows password reset by entering username

✅ **Dashboard**

* Welcomes the logged-in user
* Option to logout and return to login page

✅ **Attractive UI**

* Random background images each time the window opens
* Styled labels and buttons for a modern look

---

## 🗂️ Project Structure

```
project_folder/
│
├── main.py                 # The main application file
├── secure_users.db         # SQLite database (auto-created)
├── bg1.jpg                 # Background image 1
├── bg2.jpg                 # Background image 2
└── bg3.jpg                 # Background image 3
```

> 🖼️ Make sure you have at least three background images (`bg1.jpg`, `bg2.jpg`, `bg3.jpg`) in the same folder as the script.

---

## 💻 Requirements

Install the required libraries:

```bash
pip install pillow
```

Python’s built-in libraries used:

* `tkinter`
* `sqlite3`
* `hashlib`
* `re`
* `random`

You don’t need to install these separately.

---

## 🚀 How to Run

1. Save the script as **main.py**.
2. Place your background images (`bg1.jpg`, `bg2.jpg`, `bg3.jpg`) in the same directory.
3. Open a terminal or command prompt in that directory.
4. Run the program:

   ```bash
   python main.py
   ```
5. The login window will appear.

---

## 🧩 Usage Flow

1. **Register a new account**

   * Click *Register*
   * Enter *username*, *email*, and *password*
   * Password must be at least 6 characters
   * Click *Register*

2. **Login**

   * Enter *username* and *password*
   * Click *Login*
   * If correct → Dashboard opens

3. **Forgot Password**

   * Click *Forgot Password*
   * Enter *username* and *new password*
   * Click *Reset Password*

---

## 🔐 Security Notes

* Passwords are never stored in plain text; they are hashed using **SHA-256**.
* Email validation uses regex for basic structure checking.
* SQLite ensures persistent local data storage.

---

## 🧠 Future Enhancements

* Add email OTP verification.
* Add password confirmation during registration.
* Strengthen password policy (special characters, etc.).
* Use a secure database or integrate with a cloud-based DB.

---

## 👨‍💻 Author

**Developed by:** vijay selvan y
**Language:** Python 3.x
**Libraries:** Tkinter, SQLite3, Pillow

---

⭐ **Tip:** This project is ideal for beginners learning **GUI + Database integration** with **Tkinter** and **SQLite**.
