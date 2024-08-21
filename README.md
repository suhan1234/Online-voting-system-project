# Online-voting-system-project

Online voting system using PHP

This is a complete Online Voting System I created for my final year project for the University of Lusaka in Zambia. This system is a PHP Project that provides an online platform to vote. The system was developed for a specific school. This project stores the candidate details, voters details, and etc. The voters in this project are the student of the school and in order for them to vote, they must register their system account and their student ID number is required. After the student registration to the system, the system admin user will activate the student accounts so they could vote for their candidates. The system has 3 types of users which are the Admin, Staff, and Voters. The admin can manage all of the data in this system and the staff has only limited access to manage the data. This Voting System generates a printable report for the total counts of the vote for all candidates.

The project was developed using PHP/Mysqli, MySQL Database, HTML, CSS, Javascript (jQuery and Ajax), and Bootstrap for the design. The system source code is free to download. Just follow the instructions that are provided below to run the project properly.

Features
Admin Side

Login/Logout
Manage Candidate
Activate/Deactivate Voters
Manage Students
Generate Election Report
Manage User/Staff List
View User Time Logs
Staff Side

Login/Logout
Manage Candidate
View Voters List
Manage Students
Generate Election Report
View User/Staff List
Voters

Register to the system
Vote
How to Run
Requirements

Download and Install any local web server such as XAMPP/WAMP.
Download the provided source code zip file. (download button is located below)
Installation/Setup

Open your XAMPP/WAMP's Control Panel and start the "Apache" and "MySQL".
Extract the downloaded source code file.
If you are using XAMPP, copy the extracted source code folder and paste it into the XAMPP's "htdocs" directory. And If you are using WAMP, paste it into the "www" directory.
Browse the PHPMyAdmin in a browser. i.e. http://localhost/phpmyadmin
Create a new database naming "vote".
Import the provided SQL file. The file is known as "vote.sql" located inside the "database" folder.
Browse the Online Coting System in a browser. i.e. http://localhost/voting
( Admin Access Information =>
Login ID: 1 ,
Username: admin ,
Password: admin  )

 ( User Access Information =>
Login ID: 4   ,
Username: user  ,
Password: user  )
