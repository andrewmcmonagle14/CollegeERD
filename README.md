# CollegeERD
CSCI 366 Database Systems: Assignment 2: Conceptual ERD Diagram
Instructions: 
In conceptual level design, we will focus on capturing data requirement (entity types and their relationships) from the requirement. You don’t need to worry about the actual database table structures at this stage. 
Consider following requirement to build a mini university management system:
1.	The university has many colleges, each college has a unique name, a location, a dean to lead the college.
2.	Each college has many departments (at least one), department has unique name, mailing address, students and faculties.
3.	One faculty can only belong to one department.
4.	Department offer many different classes. Class is taught by one and only one faculty.
5.	Student can register many classes and we want to store a timestamp when they registered each class, and a student can belong to many departments.
6.	We want to track class number, name, instructor, and classroom  for a class. Class can have 0 or many students.
7.	The system needs to store students id (unique), name, phone, address, gender, birthdate.
8.	The system needs to store faculties id (unique), name, phone, address, gender, birthdate, highest degree.
