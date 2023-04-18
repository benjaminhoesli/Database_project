Instructions:

- To run the project, copy the sql code into a sql editor of your choice.
- In order to see all tasks execute at once, run all the code at once. The tasks will be executed step by step.
- If you would like to see the task 4-12 execute individually, comment out all the tasks that you do not want to execute. Task 4-12 are indicated in the sql file.
- Task 1-3 are here to set up the tables and fedd them with relevant data. While they should not be commented out, they can be modified with different data.


The Project:

#Create a Grade Book Database
1. Problem Statement
You are asked to implement a grade book to keep track student grades for several couses that a professor teaches. Courses should have the information of department, course number, course name, semester, and year.  For each course, the grade is caculated on various categories, including course participations, homework, tests, projects, etc.  The total percentages of the categories should add to 100% and the total perfect grade should be 100. The number of assignments from each category is unspecified, and can change at any time.  For example, a course may be graded by the distribution: 10% participation, 20% homework, 50% tests, 20% projects. Please note that if there are 5 homework, each homework is worth 20%/5=4% of the grade.

　

2. Tasks

1: Design the ER diagram;

2:Write the commands for creating tables and inserting values;

3:Show the tables with the contents that you have inserted;

4:Compute the average/highest/lowest score of an assignment;

5:List all of the students in a given course;

6:List all of the students in a course and all of their scores on every assignment;

7:Add an assignment to a course;

8:Change the percentages of the categories for a course;

9:Add 2 points to the score of each student on an assignment;

10:Add 2 points just to those students whose last name contains a ‘Q’.

11:Compute the grade for a student;

12:Compute the grade for a student, where the lowest score for a given category is dropped.


Test cases:

The test cases in tests.sql can be commented out and then uncommented one by one in order to see the seperate outputs.
The outputs are in the outputs folder.
task 4-12 can also be used as test cases.



