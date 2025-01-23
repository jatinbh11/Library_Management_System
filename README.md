# Library Management System

## Description
The **Library Management System** is a Python-based project designed to manage book records and borrowing activities efficiently. It provides an intuitive graphical user interface (GUI) for librarians and students to issue, return, and track books. The system is backed by a MySQL database for storing book details and transaction records.

## Features
- **Book Management**: Add, update, and delete book records.
- **Borrow & Return System**: Issue books to students and track return dates.
- **Student Management**: Maintain borrowing records for students.
- **Fine Calculation**: Automatic fine calculation for late returns.
- **Search Functionality**: Search books by title, author, or edition.
- **User-friendly GUI**: Developed using Tkinter for easy interaction.

## Requirements
- Python 3.x
- MySQL Server
- Tkinter
- PyMySQL

## Installation

1. **Clone the repository**:
   ```sh
   git https://github.com/jatinbh11/Library_Management_System.git
   cd library-management-system
   ```

2. **Install dependencies**:
   ```sh
   pip install PyMySQL
   pip install tk
   ```

3. **Setup MySQL Database**:
   - Create a database named `library_management` in MySQL.
   - Ensure the necessary tables (`book_list` and `borrow_record`) are created.
   
4. **Run the application**:
   ```sh
   python main.py
   ```

## Usage
- **Librarians** can add, update, and remove books.
- **Students** can borrow and return books.
- **Admins** can manage users and book inventory.



