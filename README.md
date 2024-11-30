**Student** **Grade** **Tracker**

A Python program to track students' grades and marks for different
subjects, calculate subject-wise averages, and display overall averages.

**Features**

> 1\. **Add** **Student**: Easily add a new student to the system by
> name.
>
> 2\. **Add** **Grade**: Assign grades (e.g., A, B, C) and numerical
> marks for different subjects to each student.
>
> 3\. **Subject-Specific** **Averages**: Calculate and display the
> average marks for each subject. 4. **Overall** **Averages**: Compute
> the overall average marks across all subjects for a student. 5.
> **View** **All** **Students**: View a detailed summary of each
> student's grades, marks, and
>
> averages.

**How** **to** **Run**

**Prerequisites**

> • Python 3.7 or higher installed on your system.

**Steps**

> 1\. Clone or download this repository.
>
> 2\. Open a terminal or command prompt in the project folder. 3. Run
> the program:
>
> bash
>
> Copy code
>
> python student_grade_tracker.py
>
> 4\. Follow the on-screen instructions to use the application.

**Program** **Flow**

> 1\. **Menu** **Options**:
>
> o Add a new student.
>
> o Add a grade and marks for a specific student and subject. o View all
> students' grades and averages.
>
> o Exit the program.
>
> 2\. **Input** **Validation**:
>
> o Only grades from the scale A, B, C, D, Fare accepted. o Marks must
> be a valid number.
>
> 3\. **Calculations**:
>
> o **Subject** **Average**: The program calculates the average marks
> for each subject. o **Overall** **Average**: The program calculates
> the average marks across all subjects
>
> for a student.

**Example** **Interaction**

> 1\. **Adding** **a** **Student**: o Input: John
>
> 2\. **Adding** **Grades**:
>
> o Subject: Math, Marks: 85, Grade: A
>
> o Subject: Science, Marks: 70, Grade: B 3. **Viewing** **Students**:
>
> yaml
>
> Copy code Student: John
>
> Math: \[85 (A)\], Average Marks: 85.00 Science: \[70 (B)\], Average
> Marks: 70.00
>
> Overall Average Marks: 77.50

**Code** **Overview**

> • **StudentClass**:
>
> o Manages student details, grades, and marks.
>
> o Calculates averages for each subject and overall. •
> **GradeTrackerClass**:
>
> o Manages the list of students and user interactions.
>
> o Provides options to add students, grades, and view all records.

**Future** **Enhancements**

> • **Export** **Data**: Add functionality to export student records to
> a file (CSV or JSON). • **Import** **Data**: Allow importing student
> records from a file.
>
> • **Grade-to-Marks** **Conversion**: Add automated grade-to-mark
> mapping. • **GUI**: Implement a graphical user interface for easier
> interaction.
