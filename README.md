# Student Management System

![Java](https://img.shields.io/badge/Java-8-orange)
![MySQL](https://img.shields.io/badge/MySQL-8.0-blue)

## Project Overview

The Student Management System is a Java-based application developed to manage students' full course history. The project was carried out from August 2022 to November 2022, utilizing Java for the backend logic and MySQL for database management.

## Features

- **Student Records**: Manage student information, including personal details and academic records.
- **Course Management**: Add, update, and manage course details linked to students.
- **Database Integration**: Persistent storage of student and course data using MySQL.
- **Search Functionality**: Efficiently search for students and courses within the system.

## Tools & Technologies

- **Java**: The primary programming language used for developing the application logic.
- **MySQL**: Used for managing the database, storing student and course information.

## Installation

To set up the Student Management System locally, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/Afsana-Setu/Student-Management.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Student-Management
    ```

3. Set up the MySQL database:

    - Create a new database in MySQL.
    - Import the provided `student_management.sql` file into your MySQL database.
    - Update the database connection details in the `dbconfig.java` file with your MySQL credentials.

4. Compile and run the Java application:

    ```bash
    javac Main.java
    java Main
    ```

5. Follow the on-screen instructions to use the system.

## Project Structure

```
Student-Management/
│
├── src/
│   ├── Main.java               # Entry point of the application
│   ├── Student.java            # Class to manage student data
│   ├── Course.java             # Class to manage course data
│   ├── DatabaseManager.java    # Class to handle database operations
│   └── dbconfig.java           # Database configuration file
│
├── sql/
│   └── student_management.sql  # SQL script to set up the database
│
├── README.md                   # Project documentation
└── LICENSE                     # License for the project
```

## Usage

1. **Adding Students**: Use the application interface to add new students to the system.
2. **Managing Courses**: Assign courses to students and update their progress.
3. **Viewing Records**: Search and view detailed student records, including course history.
4. **Updating Information**: Modify student or course details as needed.

## Future Improvements

- **User Interface**: Implement a graphical user interface (GUI) for better usability.
- **Role-Based Access**: Add authentication for different user roles (e.g., admin, teacher).
- **Reporting**: Generate detailed reports of student progress and course completion.

## Acknowledgments

- Java documentation
- MySQL community for their extensive resources and support

## Project Link

[Student Management System](https://github.com/Afsana-Setu/Student-Management)

---
