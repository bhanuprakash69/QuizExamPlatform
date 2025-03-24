
# Quiz Platform

This project is a simple quiz platform developed using Java Swing and MySQL. The application allows students to register and participate in online exams. It consists of three main classes: `OnlineExam`, `Student`, and `QuizBox`.

## Classes

### OnlineExam

The entry point of the application, initializing the student login interface.

### Student

Handles student registration and login functionality. Connects to a MySQL database to store and retrieve student information.

Key features:
- Establishes a connection to the MySQL database.
- Inserts new student data into the database.
- Validates if the roll number already exists.
- Launches the quiz interface upon successful registration.

### QuizBox

Represents the quiz interface that is displayed to the student after successful registration.

## Database

The application uses a MySQL database named `onlineexam` with a table `student` to store student details.

## Getting Started

### Prerequisites

- Java Development Kit (JDK)
- MySQL Server
- JDBC Driver for MySQL

### Setup

1. Clone the repository:
   ```sh
   git clone https://github.com/bhanuprakash69/QuizExamPlatform.git
   ```

2. Set up the MySQL database as described in the project documentation.

3. Update the database connection details in the `Student` class if necessary.

4. Compile and run the application:

   - The Application was developed on netbeans
   - So download the repository and open the files in netbeans
   - Then download the Executable jar file to run the application
   - Make sure the MySQL database URL will change accordingly to your machine

