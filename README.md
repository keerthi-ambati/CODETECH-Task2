# CODETECH-Task2
**NAME :** AMBATI KEERTHI

**COMPANY :** CODETECH IT SOLUTIONS

**ID :** CTO8DS1789

**DOMAIN :** JAVA PROGRAMMING

**DURATION :** 10TH JUNE 2024 TO 10TH JULY 2024

**MENTOR :** G.SRAVANI

**OVERVIEW OF THE PROJECT :**

**PROJECT :** STUDENT GRADE TRACKER

**OUTPUT:**
![Screenshot 2024-06-18 234016](https://github.com/keerthi-ambati/CODETECH-Task2/assets/139665917/4744eb7d-16ed-40c7-a436-2e770d672477)

**OVERVIEW :**

>GradeTracker is a simple Java application that allows users to input grades for various subjects, calculate the average grade, determine the corresponding letter grade, and calculate the GPA (Grade Point Average) based on the input grades.

**FEATURES:**

>Input grades for multiple subjects.

>Calculate the average grade.

>Determine the letter grade based on the average grade.

>Calculate the GPA based on the average grade.


**TECHNOLOGY USED :**

>Java: The primary programming language used to develop the application.

>Java Standard Library: Utilized for basic operations such as user input (Scanner) and data storage (HashMap).

**REQUIREMENTS :**

>Java Development Kit (JDK) 8 or higher

**HOW TO USE :**

>Compile the program:

>**Input grades:**

The program will prompt you to enter the subject name. Type the subject name and press Enter.

Next, you will be prompted to enter the grade for the subject. Type the grade (as a double) and press Enter. 

Repeat the steps to input more subjects and grades.

Type exit as the subject name to stop entering grades and to calculate the results.

**View results:**

The program will display the overall average grade, the corresponding letter grade, and the GPA.

**EXAMPLE USAGE :**

Welcome to the Grade Tracker!

Enter subject name (or 'exit' to quit): Math

Enter grade for Math: 95.0

Enter subject name (or 'exit' to quit): English

Enter grade for English: 88.5

Enter subject name (or 'exit' to quit): History

Enter grade for History: 76.0

Enter subject name (or 'exit' to quit): exit


Overall Grade: 86.5

Letter Grade: B

GPA: 3.0

**CODE EXPLANATION :**

>The main components of the GradeTracker program are:

>**CONSTANTS:**

A_THRESHOLD, B_THRESHOLD, C_THRESHOLD, and D_THRESHOLD: Define the grade thresholds for letter grades.

**MAIN METHOD:**

Initializes a Scanner object for user input and a HashMap to store subject names and their corresponding grades.

Continuously prompts the user to input subject names and grades until the user types exit.

Includes error handling to ensure valid numeric grades between 0 and 100.

Calculates the total grade and the number of subjects.

Computes the average grade, determines the letter grade, and calculates the GPA.

**Helper Methods:**

getLetterGrade(double grade): Determines the letter grade based on the grade thresholds.

getGPA(double grade): Calculates the GPA based on the grade thresholds.











