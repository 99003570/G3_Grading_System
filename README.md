# G3_Grading_System


# Folder Structure
Folder             | Description
-------------------| -----------------------------------------
`requirements`   | Documents detailing high level and  low  level requirements.
`design`         | Documents specifying structural and behavioural diagrams.
`Implementation` | All code and documentation including source code and header files.
`Test Plan`      | Documents with test cases codes and there positive and negative outputs.


 

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
|**Test Case       ID**|<p>`       `**Test Case**  </p><p>`   `**Scenario**</p>|**Expected Output**|` `**Actual output**|<p></p><p>**STATUS**</p>|
| :- | :- | :- | :- | :- |
|1.|Entering the PSNumber of length equals to 8|Pass.|Pass.|Pass.|
|2.|Entering less than 12 characters.|OOPS! Password must be at least 12 to 16 characters.|OOPS! Password must be at least 12 to 16 characters.|Pass.|
|3.|Entering password without capital letter.|OOPS! Weak password, Enter at least one capital letter.|OOPS! Weak password, Enter at least one capital letter.|Pass.|
|4.|Entering password without small letter.|OOPS! Weak password, Enter at least one small letter.|OOPS! Weak password, Enter at least one small letter.|Pass.|
|5.|Entering password without numeric value.|OOPS! Weak password, Enter at least one numeric value.|OOPS! Weak password, Enter at least one numeric value.|Pass.|
|6.|Entering password without special character.|OOPS! Weak password, Enter at least one special letter.|OOPS! Weak password, Enter at least one special letter.|Pass.|
|7.|Entering 17 characters.|OOPS! Weak password, Password must be at least 12 to 16 characters.|<p>OOPS! Weak password, Password must be at least 12 to 16 characters.</p><p></p>|Pass.|
|8.|Entering 11 characters.|OOPS! Password must be at least 12 to 16 characters.|OOPS! Password must be at least 12 to 16 characters.|Pass.|
|9.|Enter how many times user wants to save password, if user enter zero than program terminates |Program terminated|Program terminated|Pass.|
|10.|User want to save the suggested password than enter 1|Your password is saved, your password is: -|Your password is saved, your password is :-|Pass.|
|11.|User don’t want to save the suggested password than enter 0 for entering manual password|Enter your password: -|Enter your password: -|Pass.|


