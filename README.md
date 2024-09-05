# ExaminationSystem
This project is an Automated Examination System designed to facilitate online exams, from question generation to grading, and provide real-time reporting for ITI staff and instructors. The project includes the development of an SQL Server database, the creation of stored procedures for managing exam processes, and the generation of reports using Report Builder, SSRS. Additionally, I built Power BI dashboards to visualize key data insights.

1.Entity Relationship Diagram (ERD) & Mapping:
Designed a comprehensive ERD that maps out the relationships between students, instructors, courses, exams, and other related entities within the examination system.
![System ERD](https://github.com/user-attachments/assets/5e6c74a7-2c83-4387-b3fe-7c3baf69a8d2)
![System Mapping](https://github.com/user-attachments/assets/a558e30a-d43d-4c5b-9ff9-f79e67b39f75)

2.Database Design & Backup:
 Created an SQL Server database from scratch, covering all tables, constraints, relationships, and backup functionality for data recovery.
 ![db diagram](https://github.com/user-attachments/assets/1f263245-04fb-4c93-87a4-91887478b4a9)

 3.Stored Procedures:
    Insert, Update, Delete: Developed stored procedures for CRUD operations across all tables.
    Exam Generation: A procedure to generate exams by selecting questions from the database, organizing them by type (MCQ, T/F).
    Exam Answers: Stored procedure to insert student answers for a given exam, with questions displayed by number.
    Exam Correction: A procedure for grading exams by comparing student answers to correct answers in the database.
![sp3](https://github.com/user-attachments/assets/d58a226f-4843-443d-b1ea-7ebffa0c4226)
![sp2](https://github.com/user-attachments/assets/8cd942dc-229a-4bc7-9256-26684333a0ff)
![sp1](https://github.com/user-attachments/assets/2c4742f8-b815-4b54-bbb3-df61ada372e6)
 
4.Reports for the Staff using Report Builder:
Student Information by Department: Returns details of students filtered by department number.
Student Grades by ID: Displays a report of a student's grades across all courses, expressed as a percentage.
Instructor Courses: Takes the instructor's ID and returns the courses they teach, including the number of students enrolled per course.
Course Topics: A report that shows the topics covered by a specific course, filtered by course ID.
Exam Questions and Choices: Freeform report that lists all the questions in an exam along with the available choices.
Student Exam Answers: Returns a list of questions in a specific exam alongside the student’s answers, filtered by exam number and student ID.

Power BI Dashboards:
Developed  Power BI dashboards to provide advanced data visualization and insights related to student performance, exam statistics, and instructor activities.
![4](https://github.com/user-attachments/assets/1eddecc1-8394-4f3d-aded-dab6fffdac6d)
![3](https://github.com/user-attachments/assets/300f1fa5-3b3c-4892-832b-6917ce29e46f)
![2](https://github.com/user-attachments/assets/47f27093-4d67-4cde-857c-9e6d5bb237bc)
![Capture](https://github.com/user-attachments/assets/56fd46ce-4a25-4e1e-893f-b5a4df25e33b)













  


    

