# Course-Management-System
## Overview
A JavaFX-based GUI application designed for managing a 1-year certificate program with 30 credits and 8 courses. This system supports role-based modules for Admins, Lecturers, and Students, enabling secure login, course creation and assignment and student self-registration with prerequisite enforcement. The application ensures adherence to credit limits and provides clear course tracking for all users.

## User Panels & Key Features
### Admin 
- Create and manage student and lecturer profiles.
- Create and assign courses to lecturers.
- View all students and lecturers associated with each course.
Below is the screenshot showcases a key function of the Admin Panel, enabling the admin to view available courses and dynamically add new courses, update course information, and assign lecturers.
![Admin Panel](https://github.com/user-attachments/assets/672b32c8-d510-4a82-9a9a-1e0e61bc46b4)

### Lecturer
- View a list of all students enrolled in their assigned courses.

### Student
- Self-register for courses each trimester, with prerequisite and credit load validation.
![Student Register Panel](https://github.com/user-attachments/assets/8ee8e558-a84b-44b5-b3e1-c4c9e09bdced)
- View past, current, and future enrolled courses.
![Student Course Panel](https://github.com/user-attachments/assets/740726f4-d9b9-4711-8233-91870d445bfa)

## Installation 
1. Run `git clone "Repository Link"`
2. Add [fontawesomefx-8.2.jar](fontawesomefx-8.2.jar) file to your project's Reference Library
5. Run the Application</br>
   Launch using `Main.java`</br></br>
   **Login Credentials** (for Testing)</br>
   To login as Admin => ID: `1001` Pass: `ivan123`</br>
   To login as Lecturer => ID: `1001` Pass: `karen123`</br>
   To login as Student => ID: `1002` Pass: `nico123`

## Tools Used
[![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?logo=openjdk&logoColor=white)](#)
![FXML](https://img.shields.io/badge/FXML-XML-blue?style=flat)
