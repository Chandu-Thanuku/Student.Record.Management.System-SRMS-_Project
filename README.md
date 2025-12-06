🎓 Student Management System (C Program)

This is a simple Student Record Management System written in C language using file handling.
It supports two types of users: Admin and User, with different access levels.

🔐 Login System

The program reads login credentials from a file:

📌 credentials.txt format

username password role


Example:

admin admin123 ADMIN
john john123 USER

📁 Student Records

All student information is stored inside a file:

📌 students.txt format

roll name marks


Example:

101 Ravi 87.50
102 Anu 91.00

📌 Features
👨‍💼 Admin Privileges
Feature	Description
Add Student	Insert new student record
Display Students	View all student records
Search Student	Search by roll number
Update Student	Modify student details
Delete Student	Remove a student record
Logout	Exit to login
👨‍🎓 User Privileges
Feature	Description
Display Students	View all student details
Search Student	Find a particular student
Logout	Exit
🛠️ How to Run

Compile the program:

gcc student_management.c -o student


Run the executable:

./student


Make sure the following files exist in the same folder:

students.txt
credentials.txt

📌 File Structure
📦 Student Management System
 ├── student_management.c
 ├── students.txt
 ├── credentials.txt
 └── README.md

📎 Notes

Program uses sequential file processing.

Updating & deleting records is done using a temporary file method.

Works on any standard GCC compiler.

✨ Future Improvements (optional)

Password masking (hide entered password)

Input validation for names & marks

GUI-based interface

Prevent duplicate roll numbers
