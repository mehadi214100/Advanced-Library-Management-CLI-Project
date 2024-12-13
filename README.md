# Advanced Library Management CLI Project

## **Table of Contents**
- [Project Description](#project-description)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation Guide](#installation-guide)
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

## **Installation Guide**
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/advanced-library-management-cli.git
   ```
2. **Navigate to the Project Directory**:
   ```bash
   cd advanced-library-management-cli
   ```
3. **Ensure Python is Installed**:
   Ensure you have Python 3.7 or higher installed. You can check by running:
   ```bash
   python --version
   ```
4. **Install Required Libraries** (if any):
   ```bash
   pip install -r requirements.txt
   ```
   *(Note: This project primarily uses standard Python libraries, so a requirements file may not be needed.)*

---

## **How to Use**
1. Run the main script to start the application:
   ```bash
   python libray.py
   ```
2. Follow the on-screen prompts to navigate through the system:
   - Choose options from the menu (e.g., Add Book, View All Books).
   - Provide necessary inputs as prompted.
3. View and manage your library seamlessly through the CLI.

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

