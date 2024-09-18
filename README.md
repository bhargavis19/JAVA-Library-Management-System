# JAVA-Library-Management-System

This is a **Java-based Library Management System** designed to manage library operations such as borrowing and returning books. The system allows librarians to manage the inventory of books and track students borrowing them.

## Features

- Borrow and return books
- Track borrowed books
- Manage library inventory
- Store book data in text files
- Connect to MySQL for enhanced database operations (optional)

## Project Structure

- `OfflineLibrary.java`: The main class that contains the functionality of the library system.
- `Student.java`: A class that represents students who borrow books.
- `lib.java`: A class that handles the library book inventory and related operations.
- `librarian.java`: A class representing the librarian in charge of library operations.
- `borrowed_books.txt`: A text file storing records of currently borrowed books.
- `returned_books.txt`: A text file storing records of returned books.
- `mysql-connector-j-8.2.0.jar`: A JDBC connector for MySQL (used if the system is integrated with a MySQL database).
- Additional book data files (e.g., `computer networks.txt`, `data science.txt`) represent book categories in the library.

## Getting Started

### Prerequisites

- **Java Development Kit (JDK)**: Ensure that you have JDK installed. You can download it from [here](https://www.oracle.com/java/technologies/javase-downloads.html).
- **MySQL (optional)**: Install MySQL if you wish to use the database integration.
- **JDBC Connector**: The `mysql-connector-j-8.2.0.jar` is already included in the project.

### Setup and Run

1. Clone or download this repository.
2. Compile the Java files:
   ```bash
   javac OfflineLibrary.java
   ```
3. Run the main class:
   ```bash
   java OfflineLibrary
   ```

### Database Setup (Optional)

If you wish to integrate MySQL for storing library records:

1. Install MySQL and configure a database.
2. Update the connection details in the `lib.java` file to match your MySQL database credentials.
3. Ensure that the MySQL connector (`mysql-connector-j-8.2.0.jar`) is on your classpath.

