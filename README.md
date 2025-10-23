# 📚 Library Management System (Java)

A simple **console-based Library Management System** built in Java.
It allows users to **add, view, issue, and return books** easily through a command-line menu.

---

## 🚀 Features

* Add new books with ID, title, and author.
* View all available and issued books.
* Issue a book by its ID.
* Return an issued book.
* User-friendly console interface.

---

## 🧠 How It Works

1. When you run the program, a menu is displayed with 5 options:

   * **1:** Add a new book.
   * **2:** View all books.
   * **3:** Issue a book (mark as issued).
   * **4:** Return a book.
   * **5:** Exit the program.
2. Books are stored in an `ArrayList` inside the `Library` class.
3. Each book has:

   * `id`
   * `title`
   * `author`
   * `isIssued` (status: Issued/Available)

---

## 🧩 Classes Overview

* **Book** – Represents a single book.
* **User** – Represents a user (can be extended for tracking).
* **Library** – Handles all book operations (add, issue, return, view).
* **LibraryManagement (main)** – Displays menu and takes user input.

---

## 💻 How to Run

1. Save the code as `LibraryManagement.java`.
2. Open a terminal and compile:

   javac LibraryManagement.java
   
3. Run the program:

   java LibraryManagement

---

## 🧾 Example Output

--- Library Management System ---
1. Add Book
2. View Books
3. Issue Book
4. Return Book
5. Exit
Choose an option: 1
Enter ID: 101
Enter Title: Java Programming
Enter Author: Pavankumar
Book added successfully!

Choose an option: 2
101 | Java Programming | Pavankumar | Available

---

## 🧰 Technologies Used

* Language: **Java**
* Library: **java.util** (for Scanner and ArrayList)

---

## 👨‍💻 Author

Muthyamaina Pavan Kumar

💼 Full Stack & Java Developer
