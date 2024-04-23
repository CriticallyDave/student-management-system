# Student Management System

This Python application provides an interface to manage student records using a simple SQLite database. It leverages the PyQt6 framework for its graphical interface.
Features

    Add students: Input and store student information (name, course, mobile number).
    Edit students: Update the details of existing student records.
    Delete students: Remove student records from the database.
    Search students: Find students by name.
    Data display: Organize and display student records in a clear table format.

## Getting Started
### Prerequisites

    Python 3 (https://www.python.org/downloads/)
    PyQt6 (pip install PyQt6)
    SQLite3 (Usually built into Python)

### Installation

    Clone this repository:
    Bash

    git clone https://github.com/your_username/student-management-system.git


Navigate to the project directory:
Bash

cd student-management-system


### Running the Application

Execute the main Python file:
Bash

python main.py 

### Database Setup

The application expects a database file named 'database.db' in the project's root directory.
If the database file doesn't exist, it will be created automatically.
The application assumes a table named 'students' within the database with the following columns:
    
    id (integer, primary key)
    name (text)
    course (text)
    mobile (text)

### Usage

    Adding a student: Click the "Add Student" button, fill in the details in the dialog box, and click "Register".
    Searching for a student: Use the "Search" option, enter the student's name, and click "Search".
    Editing a student: Select a student record in the table and click the "Edit Record" button on the status bar. Make changes in the dialog box and click "Update".
    Deleting a student: Select a student record in the table and click the "Delete Record" button on the status bar. Confirm the deletion in the dialog box.

