# G3_Grading_System


# Folder Structure
Folder             | Description
-------------------| -----------------------------------------
`requirements`   | Documents detailing high level and  low  level requirements.
`design`         | Documents specifying structural and behavioural diagrams.
`Implementation` | All code and documentation including source code and header files.
`Test Plan`      | Documents with test cases codes and there positive and negative outputs.

# Requirements

Develop a User Interface for the grading system that will display the trainee marks and adding the module marks if faculty wants to add and operations team to add new batch,new trainee,new track and module.

# Design

**UseCase Diagram**

![](https://github.com/99003570/G3_Grading_System/blob/main/UseCaseDiagram.png?raw=true)

**Class Diagram**

 ![](https://github.com/99003570/G3_Grading_System/blob/main/LLD.jpg?raw=true)

# Contributors List and Issue Tracker 

Name                           |   PS No.  |    Features           
-------------------------------|-----------|----------------
`1) Sanidya Sharan`             | 99003570  | Created batch table,Coding on batch table and Unit Testing 
`2) Omisha Mahere`          | 99003679  | Created trainee table,Coding on Trainee table and Unit Testing
`3) Maddu Hema Supriya `   | 99003552  |Created Module Marks table, Coding on Module Marks  table and Unit Testing
`4) Mohammad Arsalaan Ansari`             | 99003675  |Created Track table, Coding on Track table and Unit Testing
`5) Meduri NJ Srilekha`             | 99003546  | CreatedModule table, Coding on Module table and Unit Testing 
    
# Challenges

1. We faced challenges in creating the hyperlinks.
2. We faced challenges in unit testing.
3. We faced challenges in adding new modules in the grading system.


# Introduction

The project is to provide a Web Application to the faculty for marking/grading system and manage the batches and courses running for the trainees. It will track all the courses, batches and modules that are running in the training place and it will have the feature to add new courses and modules to the training.


# FEASIBILITY STUDY
# WHY-
It will provide a very easy handling of marks, courses and the training details and tracking everything with the help of this system will make things easy and user friendly.

# WHEN-
This project will be used by the universities/colleges throughout the training program as it provides functionalities that run all over the year.

# WHAT-
The project is to provide a Web Application to the faculty for marking/grading system and manage the batches and courses running for the trainees. It will track all the courses, batches and modules that are running in the training place and it will have the feature to add new courses and modules to the training.

# WHERE-
This project will be accessible to anyone using a mobile phone or a PC and a working internet connection.

# HOW-
Firstly, we created a database in which tables and procedures are defined. After it with the help of the layered approcah we connected the database with the Web API project and after it adding the MVC project to the API and creting the view we displayed everything function in the web browser.


# Swot Analysis: -
  # (i). Strengths   --
      1. It will help to manage vast number of trainees in a very effective and easy way.
      2. Learning and progress report for every trainee will be monitored properly.
      3. It will reduce societal pressure and will provide the learner with more flexibility.
      4. It will lead to a focus on a better learning environment Operational
      5. It will add and update the list of the trainees in the program as per the situation.
      6. It will be able to add a new module and track and assign it to the trainees.

 # (ii). Weakness   --
      1. Narrowed down to the feature and functions provided and predefined.
      2. It is limited to one type of grading sytem i.e, standard marks grading system and not be able to calculate gardes based on percentage, mastery or narrative grading. 
      3. This system will make trainees/student marks/grades centric other than knowledge centric. 
      

 # (iii). Opportunities   --    
      1. It will help tom scale up the project to manage other aspects of the program other than trainee, for example tracking all the faculty, vendors, etc.
   

# (iv). Threats   --
     1. Malicious external and internal cybersecurity attacks can be done on the grading system.
     2. If breached into the system the data can be stolen, tampered or updated in a wrong way.
     

# Test Case Table
|**Test Case       ID**|<p>`       `**Test Case**  </p><p>`   `**Scenario**</p>|**Expected Output**|**Actual output**|<p></p><p>**STATUS**</p>|
| :- | :- | :- | :- | :- |
|1.|Entering the PSNumber of length equals to 8|Pass.|Pass.|Pass.|
|2.|Entering the PSNumber greater or less than 8|table not found|table not found|Pass.|
|3.|Entering the module marks with PsNumber|Trainee Added Successfully|Trainee Added Successfully|Pass.|
|4.|Entering the trainee cgpa with length greater than 2|table not found|table not found|Pass.|
|5.|updating the trackstatus with trackid exists in the Track|Updated track status successfully|Updated track status successfully|Pass.|
|6.|updating the trackstatus with trackid  not exists in the Track|table not found|table not found|Pass.|
|7.|Entering the length of the emailid greater than 50|table not found|table not found|Pass.|
|8.|Adding the module marks of the trainee that doesnot exist in the module marks table|added successfully|table not found|Pass.|
|9.|Adding the module marks of the trainee that exist in the module marks table|table not found|table not found|Pass.|
|10.|Adding the values beyond the length|table not found|table not found|Pass.|


