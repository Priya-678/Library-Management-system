# 📚 Library Management System in C

![C Programming](https://img.shields.io/badge/Language-C-blue)
![File Handling](https://img.shields.io/badge/Feature-File_Handling-green)
![Console Based](https://img.shields.io/badge/Interface-Console-lightgrey)

A robust console-based library management system developed in C, featuring secure user authentication, comprehensive book management, and efficient data storage using file handling.

## ✨ Key Features

### 📖 Book Management
- Add new books with complete details (ID, Name, Author, Category, Edition)
- Edit existing book records (Category, Edition)
- Delete books (soft deletion)
- View all available books in tabular format

### 🔍 Search Functionality
- Search by Book Name (partial/full match)
- Search by Author Name
- Search by Category
- View sorted books (by ID or Name)

### 👥 User System
- Role-based access (Librarian/Student)
  - **Librarian**: Full access to all features
  - **Student**: Limited to search and view functions
- Secure password handling with input masking
- Account creation and deletion

### 📅 Issue/Return System
- Book issuing with automatic due date calculation (20 days)
- Return tracking with date validation
- View all issued books with student details

## 🛠️ Technical Implementation
- **Data Structures**: Custom structures for books, users, and transactions
- **File Handling**: Persistent storage in text files (`book.txt`, `account.txt`, `issue.txt`)
- **Sorting Algorithms**: Bubble Sort (ID), Selection Sort (Name)
- **Date Handling**: Validation and due date calculation

## 🚀 Getting Started

### Prerequisites
- GCC Compiler (MinGW for Windows)
- Basic C development environment

### Installation & Execution
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/library-management-c.git
   cd library-management-c
2. Compile the source code:
   ```bash
   gcc librarymanagement.c -o library -Wall
3. Run the program:
   ```bash
   ./library   # Linux/Mac
   library.exe # Windows

## 🚀 First Run Instructions

1. **Create a Librarian Account**  
   When first running the program, you'll be prompted to create a librarian account.

2. **Initial Setup**  
   Use the menu options to:
   - Add sample books to the system
   - Create student accounts
   - Explore all available features

---

## 📝 Usage Guide

### 👨‍💼 **Librarian Access**  
*Full system control with these privileges:*
- **Book Management**
  - Add new books
  - Edit existing book details
  - Delete books from system
- **Transaction Oversight**
  - View all issued books
  - Check return status
- **User Administration**
  - Create/delete student accounts
  - Manage user privileges

### 👩‍🎓 **Student Access**  
*Limited to these functions:*
- **Book Discovery**
  - Search available books by:
    - Title
    - Author
    - Category
- **Information Viewing**
  - Check book details
  - View due dates
  - See availability status
