Student Grade Tracker
A Python program to track students' grades and marks for different subjects, calculate subject-wise averages, and display overall averages.

Features
Add Student: Easily add a new student to the system by name.
Add Grade: Assign grades (e.g., A, B, C) and numerical marks for different subjects to each student.
Subject-Specific Averages: Calculate and display the average marks for each subject.
Overall Averages: Compute the overall average marks across all subjects for a student.
View All Students: View a detailed summary of each student's grades, marks, and averages.
How to Run
Prerequisites
Python 3.7 or higher installed on your system.
Steps
Clone or download this repository.

Open a terminal or command prompt in the project folder.

Run the program:

bash
Copy code
python student_grade_tracker.py
Follow the on-screen instructions to use the application.

Program Flow
Menu Options:

Add a new student.
Add a grade and marks for a specific student and subject.
View all students' grades and averages.
Exit the program.
Input Validation:

Only grades from the scale A, B, C, D, F are accepted.
Marks must be a valid number.
Calculations:

Subject Average: The program calculates the average marks for each subject.
Overall Average: The program calculates the average marks across all subjects for a student.
Example Interaction
Adding a Student:

Input: John
Adding Grades:

Subject: Math, Marks: 85, Grade: A
Subject: Science, Marks: 70, Grade: B
Viewing Students:

yaml
Copy code
Student: John
  Math: [85 (A)], Average Marks: 85.00
  Science: [70 (B)], Average Marks: 70.00
Overall Average Marks: 77.50
Code Overview
Student Class:
Manages student details, grades, and marks.
Calculates averages for each subject and overall.
GradeTracker Class:
Manages the list of students and user interactions.
Provides options to add students, grades, and view all records.
Future Enhancements
Export Data: Add functionality to export student records to a file (CSV or JSON).
Import Data: Allow importing student records from a file.
Grade-to-Marks Conversion: Add automated grade-to-mark mapping.
GUI: Implement a graphical user interface for easier interaction.
