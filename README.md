# Student-Result-Processing


#  INTRODUCTION
An individual report card of each student has to be displayed and printed at a keystroke according to any selected format. An important aid for teachers and students to judge their performance. Merit list printing by totals for a class by individual subject marks for a class. Student performance in a particular subject or all the subjects must be expressed. Performance of teachers of various classes can be easily compared.

      Purpose

The system displays the list of all issues that are open, closed, in progress. If the user can get registered by clicking on the logon button and provide the required information as specified. Each time the registered customer come on to the site he can makes use of the user name and the password that is allocated to him.
.
   Key features
•	User configurable grading system.
•	User configurable examination pattern.
•	Examinations-weight age handling.
•	Calculated / Average Column handling.
•	Grace marks handling.
•	Special Analysis section.
•	Sub-subjects marks entry handling.



# SOFTWARE AND HARDWARE SPECIFICATIONS

 Software requirements

Operating System		:      Window 2000, XP
User interface  		:      Java, Servlets, JSP
Database		            :      My SQL
Documentation Tool	            :       Ms Office 

 Hardware requirements

Processor	       :	 Standard processor with a speed of 1.6 GHz or more
RAM	 : 	 256 MB RAM or more
Hard Disk	 : 	20 GB or more
Monitor	: 	Standard color monitor
Keyboard	: 	Standard keyboard
Mouse	:	 Standard mouse



# . SOFTWARE REQUIREMENTS ANALYSIS
     
Requirement analysis for web applications encompasses three major tasks: formulation, requirements gathering and analysis modeling. During formulation, the basic motivation and goals for the web application are identified, and the categories of users are defined. In the requirements gathering phase, the content and functional requirements are listed and interaction scenarios written from end-user’s point-of-view are developed. This intent is to establish a basic understanding of why the web application is built, who will use it, and what problems it will solve for its users.

## Scope

##  Existing System with Limitations
•	It is time consuming process as the user has to type the dbase commands. He has to remember all the commands which are difficult.
•	It is limited to a single system.
•	A user who wants only to have some information has to contact the administrator every time.
## Proposed System Features
•	User friendliness is provided in the application with various controls.
•	The system makes the overall project management much easier and flexible.
•	It can be accessed over the internet.
•	Vast amount of data can be stored.
•	There is no risk of data mismanagement at any level while the project development is under process.
•	Relationship between the administrator, owner/developer and subcontractor can be maintained very easily.
•	It provides high level of security using different protocols like https etc.

The Student Result Processing consists of 3 users or modules, they are:
•	Administrator
•	Student
•	Staff
## Administrator Module
The functionalities of Administrator are
1.	The Administrator should Login into the system with unique his/her username and password.
2.	If the username and password is valid then he can gain the access to the system.
3.	Admin views staff Personal details.
4.	Admin updates staff Personal details.
5.	Admin views student Personal details.
6.	Admin updates student Personal details.
7.	Admin views his/her own Personal details.
8.	Admin updates his/her Personal details.
9.	Admin views attendance of students.
10.	Admin updates  attendance of students
11.	Admin views Results of students.
12.	Admin updates Results of students.
13.	Admin views Schedules.
14.	Admin updates Schedules.
15.	Admin sends emails to students once marks have been entered.



The Administrator can do the following actions
1.	Login
2.	Admin Actions
1.	Views personal details
2.	updates schedules
3.	views reports
4.	updates attendance of students
3.	Logout
## Staff Module
The functionalities of Staff are
1.	The Staff should login into the system with unique her/his username and password.
2.	If the user name and password are valid then he can gain access to the system.
3.	Staff views students Personal details.
4.	Staff views his/her own Personal details.
5.	Staff updates his/her Personal details.
6.	Staff views  attendance of students.9
7.	Staff views Results of students.
8.	Staff views Schedules.
The Staff can do the following actions
1.	Login
2.	Staff Actions
1.	views personal details
2.	views attendance
3.	view results
3.	Log out

## Student Module
The functionalities of Student are
1.	The Student should login into the system with unique her/his username and password.
2.	If the user name and password are valid then he can gain access to the system.
3.	Student views his/her own Personal details.
4.	Student updates his/her Personal details.
5.	Student views attendance of students.
6.	Student views Results.
7.	Student views  Schedules
The Student can do the following actions:
1. Login
 2. Student Actions
1.	views attendance
2.	views results
3.	View Schedules
 3. Log out


3.	TESTING


Testing Methodologies 
	Black box Testing: 
	White box Testing.
	Gray Box Testing.


Testing:
•	The process of executing a system with the intent of finding an error.
•	Testing is defined as the process in which defects are identified, isolated, subjected for rectification and ensured that product is defect free in order to produce the quality product and hence customer satisfaction.
•	Quality is defined as justification of the requirements
•	Defect is nothing but deviation from the requirements 
•	Defect is nothing but bug.
•	Testing --- The presence of bugs
•	Testing can demonstrate the presence of bugs, but not their absence
•	Debugging and Testing are not the same thing!
•	Testing is a systematic attempt to break a program or the AUT
•	Debugging is the art or method of uncovering why the script /program did not execute properly.

# Testing Methodologies:
•	Black box Testing: is the testing process in which tester can perform testing on an application without having any internal structural knowledge of application.
Usually Test Engineers are involved in the black box testing.
•	White box Testing: is the testing process in which tester can perform testing on an application with having internal structural knowledge.
Usually The Developers are involved in white box testing.
•	Gray Box Testing: is the process in which the combination of black box and white box techniques are used.

Example for GUI Test cases:
T.C.
No	Description	Expected value	Actual value	Result
  
1	Check for all the features in
 the screen	The screen must contain
all the features		

2	Check for the alignment of 
the objects as per the validations	The alignment should be 
in proper way		

1.	Positive Test Cases:
•	The positive flow of the functionality must be considered
•	Valid inputs must be used for testing
•	Must have the positive perception to verify whether the requirements are justified.         
Example for Positive Test cases:
T.C.
No	Description	Expected value	Actual value	Result
1	Check for the date Time
 Auto Display	The date and time of the system must be displayed		
2	Enter the valid Roll no into the student roll no field	It should accept		

2.	Negative Test Cases:
•	Must have negative perception.
•	Invalid inputs must be used for test.
Example for Negative Test cases:
T.C.
No	Description	Expected value	Actual 
value	Result
1	Try to modify the information in date and time	Modification should not
 be allow		
2	Enter invalid data in to the student details form, click on Save	It should not accept invalid data, save should not allow		


# CONCLUSION
From a proper analysis of positive points and constraints on the component, it can be safely concluded that the product is a highly efficient GUI based component. This application is working properly and meeting to all user requirements. This component can be easily plugged in many other systems.

# FUTURE ENHANCEMENTS
Now the developed System is a web based system, it gives all the student details. In the future the results can be directly printed, and this functionality can be made available to the user. This can also be enhanced by giving the user more services such as aggregate calculation etc.,

# REFERENCES
- Herbert Schildt, Java Complete Reference, 5th edition
- Dietel and Dietel, Java How To program
- Pressman, Software Engineering, 4th edition
- Raghurama Krishnan, Database Management Systems
- http://www.java.sun.com
- http://www.oracle.com
