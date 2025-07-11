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

### First Run Instructions
 1.Create a librarian account when prompted
 2.Use menu options to:
	-Add sample books
	-Create student accounts
	-Explore all features

📝 Usage Guide
1. Librarian Access:
	-Add/Edit/Delete books
	-View all transactions
	-Manage user accounts

2. Student Access:
	-Search available books
	-View book details
	-Check due dates
