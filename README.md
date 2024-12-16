java c
Course Scheduler Final Project Part 1
You have been asked to develop a Course   Scheduling application   for   a   College. The   application will enable two types of Users to perform. their necessary   functions   to schedule courses by semester. The Admin User will   perform   multiple functions to   set   up   the database so that Students   my schedule courses. The functions   each   User   will   be able to perform. will   be described   below.
This application should have a very nice GUI   interface   and   will   be   a   database   driven   application. The database used will be   Derby. This application must   use   good   Object-         Oriented Design and Programming. The database must   use   good Object-Oriented Design and Programming. There is a very   close correlation   between   Object-Oriented Design and Database   Design. Your application design should include at   least   four classes besides the main GUI class. Your database   access should   be   in   the   classes   that   correlate with the database   tables.
This assignment is the first half of the final project   and   will   be   submitted   as   Final   Project   Part   1.
This phase of the project will implement the following Admin functions: 
Add Semester 
A semester is added to the database. The semester   is   identified   by one   name.
Add Course 
A new course is added to the database. The   course   is   identified   by the   code   for   the   course, and the description of the course.
Add Class 
A new class is added to the database. The class   is   identified   by   the   semester the   course   is offered, the code for the course, and the maximum   number   of students the   course will contain that semester.
Add Student 
A student is added to the database. The student   is   identified   by a   studentID, the   student’s first name, and the student’s   last   name.
This phase of the project will implement the following Student functions:
Schedule Class 
The student will be scheduled in the class for   the   specified   semester   if there   are seats available. If there are no seats available, the student   will   be   put   in   a   wait   status for that Class. The waiting status must be   maintained in   the   order   the   students   tried   to   schedule the class. It will display whether the student gets scheduled for   the   class   or   is   waitlisted. 
Display Schedule 
The   Display Schedule function will display the current schedule of classes for a specified student for the current semester. It will display the course code   and the   status   of the student in the class, whether scheduled or waitlisted. 
Display Classes 
The   Display Classes function will display a complete list of classes for   the   current   semester showing the course code, description, and numb代 写Course Scheduler Final Project Part 1Java
代做程序编程语言er   of seats.
Testing scenario: 
A testing scenario will be provided to assist you   in testing this   application.   It will   be   called Final   Project Part   1 Test   Script   on   Canvas.
Database considerations: 
Your database will be created but all the tables   should   be   empty when   your   project   is   submitted.
Initial NetBeans Project: 
An initial project is provided for   you   to   be   used   as   the   basis   of your final   project.   It   is   provided as a   .zip file in Week   11   in   Canvas   under the   name CourseSchedulerNameID.zip. It   MUST be used for your Final   Project. You   will   change   the   project name after you download it. There is   a video   in   Week   11   about   how   to   do   this. 
GUI Guidelines: 
The user should be required to enter   only   unknown   data.   Drop   down   lists   of   known data such as Student names, Course Codes, or   Semesters   should   be   displayed for   the user to select. Combo   Boxes should be used for the   drop-down   lists   on the   form.   When information is requested to be displayed, e.g.,   for   a   Display   command,   all   the   requested   information must be displayed. When a command   is   performed, the   results   of that command should be displayed to the user on the   same   display without   the   user   needing   to use a   Display function to see   what   was   done. 
Submission Guidelines: 
Don't forget to submit your zipped PROJECT folder and your zipped DATABASE folder. Zip the ENTIRE database folder and the ENTIRE project folder and submit the two zipped files in the assignment under one submission. 
Note: 
Your project must be renamed with the name ‘CourseSchedulerNameID’, where Name is your name and ID is your psu account id, e.g. xxx1234. The database must be created with the name ‘CourseSchedulerDBNameID’, and a username and password of java and java. All tables should be empty. 
Grading Criteria: 
In this project I will be looking for good OO design practices and this includes: 
• Use of getter and setter methods for class variables 
• Good naming of your classes, methods and variables 
• Correct use of static and non-static methods 
• The way you split this project into classes. 
• All of your updates to the database must be done using SQL statements, do not use ResultSetTableModels to update the database. 
• If a SQL statement to update the database needs to contain a variable, then you must use PreparedStatements, do not use concatenation of strings to create the SQL statement. 
The Grading Rubric for Final Project Part 1 is posted on Canvas. 
Note: Make sure you look at all the videos   about this assignment and the   Course   Scheduler   Design Layout on Canvas before   starting this   assignment.

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
