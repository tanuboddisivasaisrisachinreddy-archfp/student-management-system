Student Management System in C
The Student Management System is a C-based console application designed to manage student records efficiently using file handling and role-based authentication.
The system allows different levels of access for Admin, Staff, and Guest users, ensuring secure and controlled data management.
Features
Role-Based Login System

The application supports three user roles with different permissions:
->Admin: Add, view, search, update, and delete student records
->Staff: View and search student records
->Guest: View student records only
Student Record Operations
->Add new student
->Display all students
->Search student by roll number
->Update existing student details
->Delete student records
File Handling
->All student data is stored in students.txt
->User credentials are stored in credentials.txt
->Temporary file method is used for safe update and delete operations
How It Works
->The user logs in using a username and password.
->The credentials are verified from credentials.txt.
Based on the role, the system displays the corresponding menu.

Selected operations are performed by reading or updating students.txt.
