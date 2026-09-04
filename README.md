Student Management System Using Arrays
A simple console-based Student Management System developed using Java Arrays. This project allows users to add, search, update, and display student records.
📌 Project Overview
The Student Management System is designed to demonstrate the use of:
Java Arrays
Methods
Loops
Conditional Statements
Switch Case
Linear Search
CRUD Operations
Input Handling
🎯 Objectives
Store student records using arrays.
Add new student details.
Search students using a unique Student ID.
Update existing student information.
Display all student records.
Handle invalid or unavailable Student IDs.
🛠️ Technologies Used
Programming Language: Java
IDE: Eclipse
Data Structure: Arrays
Version Control: Git & GitHub
⚙️ Features
1. Add Student
Users can add:
Student ID
Student Name
Student Mark
The system checks whether the Student ID already exists.
2. Search Student
Students can be searched using their unique Student ID.
3. Update Student
Existing student information can be updated using the Student ID.
4. Display Students
The system displays all currently stored student records.
5. Invalid ID Handling
If the entered Student ID does not exist, the system displays an appropriate message.
📂 Project Structure
Student-Management-System-Java/
│
├── src/
│   └── studentmanagement/
│       └── StudentManagementSystem.java
│
├── README.md
└── ProjectReport.pdf
🚀 How to Run
Step 1
Install Java JDK on your computer.
Step 2
Open the project in Eclipse IDE.
Step 3
Open:
src → studentmanagement → StudentManagementSystem.java
Step 4
Right-click the Java file.
Select:
Run As → Java Application
Step 5
Use the menu displayed in the console.
===== Student Management System =====
1. Add Student
2. Search Student
3. Update Student
4. Display Students
5. Exit
💻 Sample Output
===== Student Management System =====
1. Add Student
2. Search Student
3. Update Student
4. Display Students
5. Exit

Enter your choice: 1

Enter Student ID: 101
Enter Student Name: Monish
Enter Student Mark: 85

Student added successfully!
Search Example
Enter Student ID to search: 101

Student Found!
ID   : 101
Name : Monish
Mark : 85.0
Update Example
Enter Student ID to update: 101
Enter New Name: Monish Kumar
Enter New Mark: 92

Student updated successfully!
Invalid ID Example
Enter Student ID to search: 999

Student ID not found!
🔍 Searching Algorithm
The project uses Linear Search to find a student.
Each Student ID is compared one by one until the required ID is found.
Time Complexity: O(n)
📚 Concepts Learned
Through this project, I practiced:
Array declaration and initialization
Array traversal
Methods in Java
for loops
while loops
switch statements
Conditional statements
Linear search
Basic CRUD operations
Console input/output
Handling invalid input
⚠️ Limitations
Arrays have a fixed maximum size.
Data is lost when the program terminates because no database is used.
The application is console-based.
It is intended for basic learning and demonstration.
🔮 Future Enhancements
Future versions can include:
Delete student functionality
Database integration using MySQL
GUI using Java Swing or JavaFX
Login/authentication
Sorting student records
Grade calculation
File-based data storage
👨‍💻 Author
Monish K
Java Programming Intern
📌 Internship Task
Day 4 – Task 4
Implement a Student Management System Using Arrays
This project was developed as part of my Java Programming Internship to practice arrays, methods, loops, and CRUD-style operations.
