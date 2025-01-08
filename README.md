# Student Record Management System

A simple C++ console application that allows users to manage student records, including creating, searching, modifying, and deleting records.

## Features

- **Add a new student record**: Input the student's name, roll number, and marks for five subjects (English, Math, Science, Second Language, Computer Science).
- **View a student's record**: Search for a student by roll number and display their complete academic details.
- **View all student records**: Display the details of all students stored in the system.
- **Delete a student record**: Remove a student's record using their roll number.
- **Modify a student record**: Edit an existing student's details and update them.

## How it Works

The program uses a file-based storage system (`student.dat`) to store student records persistently. Records are read and written in binary mode to ensure efficient storage and retrieval.

### Grading System

The student's average marks are calculated based on their scores in five subjects, and their grade is determined as follows:
- **A**: 90 and above
- **B**: 75 - 89
- **C**: 50 - 74
- **F**: Below 50

## Technologies Used

- **C++**: Core programming language used to build the application.
- **File I/O**: Used to store and retrieve student records in binary format.
- **Console-based application**: Simple text-based interface for user interaction.

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/student-record-management-system.git
   
2. Navigate to the project directory:
     cd StudentRecordManagementSystem

3. Compile the program:
   g++ srms.cpp -o srms

4. Run the compiled program:
   ./srms

   
