Overview
The provided Java code is a simple implementation of a Library Management System. It allows users to perform various operations such as adding books, borrowing books, returning books, and displaying the library catalog.

Class Structure
The code consists of three classes:

Book: Represents a book with attributes such as title, author, and availability.
Library: Represents a library that can hold multiple books and provides methods for adding, borrowing, and returning books.
LibraryManagementSystem: The main class that contains the program's entry point and provides a menu-driven interface for users to interact with the library.
Book Class
Attributes
title: The title of the book.
author: The author of the book.
isAvailable: A boolean indicating whether the book is available for borrowing.
Methods
borrowBook(): Marks the book as unavailable and prints a message indicating that the book has been borrowed.
returnBook(): Marks the book as available and prints a message indicating that the book has been returned.
displayBookDetails(): Prints the book's title, author, and availability.
Library Class
Attributes
books: An ArrayList of Book objects representing the library's catalog.
Methods
addBook(Book book): Adds a new book to the library's catalog.
showBooks(): Displays the library's catalog, including the title, author, and availability of each book.
borrowBook(String title): Attempts to borrow a book by title. If the book is found and available, it marks the book as unavailable and prints a message.
returnBook(String title): Attempts to return a book by title. If the book is found, it marks the book as available and prints a message.
LibraryManagementSystem Class
Methods
main(String[] args): The program's entry point. It creates a Library object, adds some initial books, and provides a menu-driven interface for users to interact with the library.
Menu-Driven Interface
The program provides a simple menu-driven interface that allows users to:

Show all books in the library
Borrow a book by title
Return a book by title
Add a new book to the library
Exit the program
Example Use Cases
Adding a new book: Enter option 4, enter the book title and author, and the book will be added to the library's catalog.
Borrowing a book: Enter option 2, enter the title of the book you want to borrow, and if the book is available, it will be marked as unavailable.
Returning a book: Enter option 3, enter the title of the book you want to return, and if the book is found, it will be marked as available.
Code Quality and Readability
The code is well-structured, readable, and follows good object-oriented design principles. The use of classes and methods makes the code modular and easy to maintain. The comments and variable names are clear and concise, making it easy to understand the code's functionality.
