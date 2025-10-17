# Mini-Library
# 📚 Mini Library Management System (Python)

## 🧠 Overview
This project is a **Mini Library Management System** built in **Python** using **lists, dictionaries, tuples, and functions**.  
It supports adding, searching, updating, deleting, borrowing, and returning books.  
The project demonstrates key programming concepts such as CRUD operations, data validation, and modular design.

---

## 🧩 Features
✅ Add, update, delete **books** and **members**  
✅ Borrow and return books with copy tracking  
✅ Prevents duplicate ISBNs and invalid genres  
✅ Borrowing limited to 3 books per member  
✅ Prevents deletion of books or members in use  
✅ Simple in-memory data handling (no external database required)

---

## 🧱 Data Structures
| Entity | Type | Description |
|---------|------|-------------|
| `books` | Dictionary | Key = ISBN, Value = details dict (`title`, `author`, `genre`, `total_copies`, `available_copies`) |
| `members` | List of Dictionaries | Each member dict has (`member_id`, `name`, `email`, `borrowed_books`) |
| `genres` | Tuple | Immutable list of allowed genres |

---

## 🧰 Project Files
| File | Purpose |
|------|----------|
| `operations.py` | Core functions (CRUD + borrow/return) |
| `demo.py` | Demo script to show system usage |
| `tests.py` | Simple unit tests using `assert` |
| `UML.png` / `UML.pdf` | UML diagram of system design |
| `DesignRationale.pdf` | Explanation of design decisions |
| `README.md` | This documentation file |

---

## ⚙️ How to Run

### 1️⃣ Run the demo
```bash
python demo.py
