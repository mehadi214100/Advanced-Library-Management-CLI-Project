# Advanced Library Management CLI Project

## **Table of Contents**
- [Project Description](#project-description)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [How to Use](#how-to-use)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)

---

## **Project Description**
The **Advanced Library Management CLI Project** is a command-line application designed to manage a library's book inventory and lending system efficiently. This project allows librarians to add, update, remove, view books, lend books, and manage borrowers with ease. It handles missing files gracefully and provides user-friendly error messages.

---

## **Features**
- **Add Books**: Add books with details such as title, author, publishing year, price, and quantity.
- **View Books**: Display the entire library inventory.
- **Update Books**: Update information about existing books.
- **Remove Books**: Delete books from the inventory.
- **Lend Books**: Issue books to borrowers and track lending information.
- **Return Books**: Manage book returns and update inventory.
- **View Borrowers**: Display the list of borrowers with their details.
- **Graceful Error Handling**: Automatically create necessary files if missing.

---

## **Technologies Used**
- **Programming Language**: Python
- **Libraries**:
  - `csv` (for managing borrower records)
  - `json` (for saving and loading book inventory)
  - `os` (for file management)
  - `datetime` (for managing timestamps and due dates)

---

## **File Structure**
```
.
├── libray.py          # Main program file
├── addbook.py         # Handles adding books to the inventory
├── viewFile.py        # Handles viewing books and borrower information
├── updateBooks.py     # Handles updating book details
├── removeBook.py      # Handles removing books from the inventory
├── returnBook.py      # Handles returning borrowed books
├── lendBook.py        # Handles lending books
├── savebook.py        # Saves data to files
├── loadBook.py        # Loads data from files
├── books.json         # Stores book inventory (auto-created if missing)
├── borrower.csv       # Stores borrower information (auto-created if missing)
```

---



### **Author**
Created with ❤️ by [Mehadi]

