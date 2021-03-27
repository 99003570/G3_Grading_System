# G3_Grading_System


# Folder Structure
Folder             | Description
-------------------| -----------------------------------------
`requirements`   | Documents detailing high level and  low  level requirements.
`design`         | Documents specifying structural and behavioural diagrams.
`Implementation` | All code and documentation including source code and header files.
`Test Plan`      | Documents with test cases codes and there positive and negative outputs.


 

# Contributors List and Issue Tracker 

Name                           |   PS No.  |    Features    | Issuess Raised |      Issues Resolved         
-------------------------------|-----------|----------------|----------------|------------------------------
`1) Sanidya Sharan`             | 99003570  |  Integrator, Actions & Workflow, Coding main method, Test plan and code    | on bugging     | workflow file and bugging issue resolved    
`2) Omisha        `          | 99003649  | Coding, analyzerStr method, test case updation | on unity workflowfile   | operation and coding issue resolved  
`3) Naresh Manjunath Moger`   | 99003601  | Coding, suggestion method, High Level Design      |on methods code         | errors are resolved          
`4) Mohammad Arsalaan Ansari`             | 99003675  | Coding random function, Low Level Design     | error          | errors are resolved          
    
# Challenges

1. We faced challenges in Unity Configuration.
2. We faced challenges in unit testing.
3. We faced challenges in git inspector.
4. We faced challenges in source code for suggesting password function.


# Introduction

The project is to provide a Web Application to the faculty for marking/grading system and manage the batches and courses running for the trainee.


# FEASIBILITY STUDY
# WHY-
It can be used to create or set a strong password for user accounts to make working online more secure.

# WHEN-
This project will be used by the universities/colleges/individual/hospitals/secure sites and the usage list are long as everybody needs a strong password to make their accounts secure as its the first priority, when it comes to the internet world.

# WHAT-
The product is password strength analyzer. It tells that minimum 12 to 16 characters are required and with minimum one capital letter,one small letter, one numeric value and one special character are required to make the password strong. If the user wants the suggested password then the user can choose to take the suggested password at the start and if not, then the user is given the option to create its own password while satisfying the conditions required for creating a strong password.


# WHERE-
This project will be accessible to anyone using a mobile phone or a PC and a working internet connection.

# HOW-
Firstly, we will give the suggested password by the help of suggestion method which generates random passwod. If suggested password is taken , its saved for the user. If suggested password is not taken, then number of passwords the user wants to saved is asked to the user. After the user tells the number of password he/she wants to enter, then the password is created and then re-entered to match both the password, and saved if the password matches, it is done by the help of analyzerstr method in which we compare the spasswords and also check that all the conditions are satisfied.


# Swot Analysis: -
  # (i). Strengths   --
      1. It will require more than 200 years to crack the password if Dictionary based algorithms are used.
      2. Difficult to guess password and do rehashing.
      3. Using every set of characters present on the keyword which makes the password complex and strong.

 # (ii). Weakness   --
      1. Difficult to memorize.
      2. If supercomputers are used to crack the password it would take less than 5 seconds. 

 # (iii). Opportunities   --    
      1.Strong and secure password gives essential protection from financial fraud.
      2.To make people aware about the benefits and necessity of strong passwords to make their accounts secure.

# (iv). Threats   --
     1. Supercomputers can crack the password easily.
     2. New method and attacks will be figured out which will make it less secure as time passes
     

# Test Case Table
|**Test Case       ID**|<p>`       `**Test Case**  </p><p>`   `**Scenario**</p>|**Expected Output**|` `**Actual output**|<p></p><p>**STATUS**</p>|
| :- | :- | :- | :- | :- |
|1.|Entering 12 to 16 characters which includes at least one capital letter, one small, letter, one special character and one numeric value.|YEAH! Password is strong.|YEAH! Password is strong.|Pass.|
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


