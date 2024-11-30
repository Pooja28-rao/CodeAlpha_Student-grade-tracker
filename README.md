<a name="br1"></a> 

**Student Grade Tracker**

A Python program to track students' grades and marks for different subjects, calculate subject-

wise averages, and display overall averages.

**Features**

1\. **Add Student**: Easily add a new student to the system by name.

2\. **Add Grade**: Assign grades (e.g., A, B, C) and numerical marks for different subjects to

each student.

3\. **Subject-Specific Averages**: Calculate and display the average marks for each subject.

4\. **Overall Averages**: Compute the overall average marks across all subjects for a student.

5\. **View All Students**: View a detailed summary of each student's grades, marks, and

averages.

**How to Run**

**Prerequisites**

·

Python 3.7 or higher installed on your system.

**Steps**

1\. Clone or download this repository.

2\. Open a terminal or command prompt in the project folder.

3\. Run the program:

bash

Copy code

python student\_grade\_tracker.py

4\. Follow the on-screen instructions to use the application.

**Program Flow**

1\. **Menu Options**:

o

o

o

o

Add a new student.

Add a grade and marks for a specific student and subject.

View all students' grades and averages.

Exit the program.

![ref1]![](data:image/jpeg;base64,/9j/4AAQSkZJRgABAQEAYABgAAD/2wBDAAEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQH/2wBDAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQH/wAARCAAFAnMDASIAAhEBAxEB/8QAGQABAAIDAAAAAAAAAAAAAAAAAAIEBggK/8QAKhAAAQMEAgEEAgEFAAAAAAAAAAIHGAFYlNUDBAUGCBESEyEUFSIyQXH/xAAUAQEAAAAAAAAAAAAAAAAAAAAA/8QAFBEBAAAAAAAAAAAAAAAAAAAAAP/aAAwDAQACEQMRAD8A7MvVftwcL1d6v9U+d8d7nHc9IeO8p369npem/A9inD4rwqqq5K1T0Up8hxV+taKTSvyhPzRCTHut7VHS5f5Fae797+P6dnl41fj7KE05FJ+vzyKpTyX+a/n+7/gAFmKDqXhvllJ2Yig6l4b5ZSdmAAig6l4b5ZSdmIoOpeG+WUnZgAIoOpeG+WUnZiKDqXhvllJ2YACKDqXhvllJ2Yig6l4b5ZSdmAAig6l4b5ZSdmIoOpeG+WUnZgAIoOpeG+WUnZiKDqXhvllJ2YACKDqXhvllJ2Yig6l4b5ZSdmAAig6l4b5ZSdmIoOpeG+WUnZgAIoOpeG+WUnZiKDqXhvllJ2YACKDqXhvllJ2Yig6l4b5ZSdmAAig6l4b5ZSdmIoOpeG+WUnZgAIoOpeG+WUnZiKDqXhvllJ2YACKDqXhvllJ2Yig6l4b5ZSdmAAig6l4b5ZSdmIoOpeG+WUnZgAIoOpeG+WUnZiKDqXhvllJ2YACKDqXhvllJ2Yig6l4b5ZSdmAAig6l4b5ZSdmIoOpeG+WUnZgAIoOpeG+WUnZiKDqXhvllJ2YACKDqXhvllJ2Yig6l4b5ZSdmAAig6l4b5ZSdmIoOpeG+WUnZgAIoOpeG+WUnZiKDqXhvllJ2YACKDqXhvllJ2Yig6l4b5ZSdmAAig6l4b5ZSdmIoOpeG+WUnZgAIoOpeG+WUnZiKDqXhvllJ2YACKDqXhvllJ2Yig6l4b5ZSdmAAig6l4b5ZSdmIoOpeG+WUnZgAIoOpeG+WUnZiKDqXhvllJ2YACKDqXhvllJ2Yig6l4b5ZSdmAAig6l4b5ZSdmIoOpeG+WUnZgAIoOpeG+WUnZiKDqXhvllJ2YACKDqXhvllJ2Yig6l4b5ZSdmAAig6l4b5ZSdmIoOpeG+WUnZgAIoOpeG+WUnZiKDqXhvllJ2YACKDqXhvllJ2Yig6l4b5ZSdmAAig6l4b5ZSdmIoOpeG+WUnZgAIoOpeG+WUnZiKDqXhvllJ2YACKDqXhvllJ2Yig6l4b5ZSdmAAig6l4b5ZSdmQr7UXS+vX+PeC+H5ODyCOxXkr2k1ry8NK8f26nIn+p/CuFX0rRVK1r+lqp8AAbn+L6HJ0PHdPpdruc3k+x1uvx8PN5DtUpTsdzkQn4Vz83wpVPyclf2r4VX9/7AAH//2Q==)

<a name="br2"></a> 

2\. **Input Validation**:

o

o

Only grades from the scale A, B, C, D, Fare accepted.

Marks must be a valid number.

3\. **Calculations**:

o

o

**Subject Average**: The program calculates the average marks for each subject.

**Overall Average**: The program calculates the average marks across all subjects

for a student.

**Example Interaction**

1\. **Adding a Student**:

o

Input: John

2\. **Adding Grades**:

o

o

Subject: Math, Marks: 85, Grade: A

Subject: Science, Marks: 70, Grade: B

3\. **Viewing Students**:

yaml

Copy code

Student: John

Math: [85 (A)], Average Marks: 85.00

Science: [70 (B)], Average Marks: 70.00

Overall Average Marks: 77.50

**Code Overview**

·

**Student Class**:

o

Manages student details, grades, and marks.

o

Calculates averages for each subject and overall.

·

**GradeTracker Class**:

o

o

Manages the list of students and user interactions.

Provides options to add students, grades, and view all records.

**Future Enhancements**

·

·

·

·

**Export Data**: Add functionality to export student records to a file (CSV or JSON).

**Import Data**: Allow importing student records from a file.

**Grade-to-Marks Conversion**: Add automated grade-to-mark mapping.

**GUI**: Implement a graphical user interface for easier interaction.

![ref1]![ref1]![ref1]

[ref1]: data:image/jpeg;base64,/9j/4AAQSkZJRgABAQEAYABgAAD/2wBDAAEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQH/2wBDAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQH/wAARCAAFAnMDASIAAhEBAxEB/8QAGQABAAIDAAAAAAAAAAAAAAAAAAIEBggK/8QAKBAAAQMDAwQCAgMAAAAAAAAAAAIHGFiU1QEDBAUGERIIIRMUFUFx/8QAFAEBAAAAAAAAAAAAAAAAAAAAAP/EABQRAQAAAAAAAAAAAAAAAAAAAAD/2gAMAwEAAhEDEQA/AOzLuv44OF3b3f3T13p3yddztHp3VOf+zwu2ug8jTZ6V0VXtua6p4KU8/a19ddFJ019kJ86baTHuN8VHT3P2PHy/e/b9OTu7avTkoTpuKT6+dxWmnUtNPdXn7/zT7AAsxQdSsN8rpOTEUHUrDfK6TkwAEUHUrDfK6TkxFB1Kw3yuk5MABFB1Kw3yuk5MRQdSsN8rpOTAARQdSsN8rpOTEUHUrDfK6TkwAEUHUrDfK6TkxFB1Kw3yuk5MABFB1Kw3yuk5MRQdSsN8rpOTAARQdSsN8rpOTEUHUrDfK6TkwAEUHUrDfK6TkxFB1Kw3yuk5MABFB1Kw3yuk5MRQdSsN8rpOTAARQdSsN8rpOTEUHUrDfK6TkwAEUHUrDfK6TkxFB1Kw3yuk5MABFB1Kw3yuk5MRQdSsN8rpOTAARQdSsN8rpOTEUHUrDfK6TkwAEUHUrDfK6TkxFB1Kw3yuk5MABFB1Kw3yuk5MRQdSsN8rpOTAARQdSsN8rpOTEUHUrDfK6TkwAEUHUrDfK6TkxFB1Kw3yuk5MABFB1Kw3yuk5MRQdSsN8rpOTAARQdSsN8rpOTEUHUrDfK6TkwAEUHUrDfK6TkxFB1Kw3yuk5MABFB1Kw3yuk5MRQdSsN8rpOTAARQdSsN8rpOTEUHUrDfK6TkwAEUHUrDfK6TkxFB1Kw3yuk5MABFB1Kw3yuk5MRQdSsN8rpOTAARQdSsN8rpOTEUHUrDfK6TkwAEUHUrDfK6TkxFB1Kw3yuk5MABFB1Kw3yuk5MRQdSsN8rpOTAARQdSsN8rpOTEUHUrDfK6TkwAEUHUrDfK6TkxFB1Kw3yuk5MABFB1Kw3yuk5MRQdSsN8rpOTAARQdSsN8rpOTEUHUrDfK6TkwAEUHUrDfK6TkxFB1Kw3yuk5MABFB1Kw3yuk5MRQdSsN8rpOTAARQdSsN8rpOTEUHUrDfK6TkwAEUHUrDfK6TkxFB1Kw3yuk5MABFB1Kw3yuk5MRQdSsN8rpOTAARQdSsN8rpOTEUHUrDfK6TkwAEUHUrDfK6TkyGvxRdL02PHzBfD8mz1BHI13deUnXXd2dNdv24m4n+T8K2Veuvtpr5+la6eAANz+l8Dc4HTuHwuVzN7qfI43H29ne6hytNNORzNxCfCt/e8KVp+Tc1+1eFa/f9gAD/9k=
