# Student Management System

A console-based Student Management System built with core Python. The application allows users to manage student records through a simple menu-driven interface. Student information is stored locally in a text file.

## Features

- Add new student records
- View all saved student records
- Search for a student using their ID
- Update student name, age, or grade
- Delete student records
- Prevent duplicate student IDs
- Handle file read and write errors

## Technologies Used

- Python
- Object-Oriented Programming (OOP)
- File Handling
- Exception Handling

## Project Structure

```text
project 1/
|-- STUDENT MANAGEMENT SYSTEM .ipynb  # Main Jupyter Notebook
|-- students.txt                      # Stores student records
|-- README.md                         # Project documentation
```

## Student Record Format

Student data is stored in `students.txt` in this format:

```text
StudentID,Name,Age,Grade
```

Example:

```text
1124,Abishek k,25,B+
```

## How to Run

1. Install Python 3.
2. Open `STUDENT MANAGEMENT SYSTEM .ipynb` in Jupyter Notebook or Visual Studio Code.
3. Run the code cell.
4. Select an option from the menu:

```text
1. Add Student
2. View All Students
3. Search Student
4. Update Student
5. Delete Student
6. Exit
```

## Core Concepts Demonstrated

- Classes and objects using `Student` and `StudentManagementSystem`
- File creation, reading, writing, and rewriting
- Functions and static methods
- Conditional statements and loops
- Input validation
- Error handling using `try` and `except`

## Author

Abishek1124-eng
