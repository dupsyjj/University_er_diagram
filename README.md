University ER Diagram


This repository contains an Enity-Relationship (ER) diagram for a unniversity system.


Scenario

A university has different faculties such as Engineering, Business, Health Sciences. Each faculty has multiple departments(e.g., Computer Science, Electrical Engineering, Marketing, Accounting). Each department offers various courses, which are taught by professors.
Each professor can teach multiple courses.



Entities

- University
- Faculty
- Department
- Course
- Professor


Relationship
- A university has many faculties
- Each faculty has many department.
- Each department offers many courses.
- Each course can br taught by multiple professors, and each professor can teach multiple courses.


Tools used 
- draw.io for ER Diagram



File Descriptions
- 'diagram.png' :ER Diagram
- ' problem_statement.txt: The scenerio provided
- ' entities_attributes.md': Breakdown of all entities and attributes
