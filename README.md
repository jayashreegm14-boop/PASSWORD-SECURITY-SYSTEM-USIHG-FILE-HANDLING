
# 🔐 Password Security System

A Python-based application that checks password strength and prevents duplicate password registration.

## 📌 Overview
Users enter passwords in a loop. The system evaluates each one, checks it against previously stored passwords, and registers it only if it is unique.

## ❗ Problem Statement
Weak and reused passwords make accounts vulnerable. This project gives instant strength feedback and enforces uniqueness.

## 🛠️ Tech Stack
- Python 3
- File Handling
- Google Colab / Jupyter Notebook

## ⚙️ Features
- ✅ Password strength check: LOW / MEDIUM / HIGH
- ✅ Duplicate password detection
- ✅ Persistent storage in password.txt
- ✅ Graceful handling of a missing file (FileNotFoundError)
- ✅ Type exit to quit

## 📊 Strength Criteria
| Level  | Condition |
|--------|-----------|
| LOW    | Less than 6 characters |
| MEDIUM | Does not meet HIGH criteria |
| HIGH   | 8+ chars with uppercase, lowercase, digit & special character |

## ▶️ How to Run
1. Clone the repo: git clone <your-repo-link>
2. Open the notebook in Google Colab / Jupyter
3. Run the cell and enter passwords

## 🖥️ Sample Output
Enter your password (or type 'exit' to quit): Jayashree@123
Password Strength: HIGH
Password Registered Successfully!

## 🚀 Future Improvements
- 🔒 Hash passwords (bcrypt / SHA-256) instead of plain text
- 🖼️ GUI using Tkinter / web version using Flask
- 📈 Check against common-password lists
