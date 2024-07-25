# Java_StudyAbroadInfoSys
The Study Abroad Information System [Version 1] provides comprehensive information about the top universities and the best courses available in various countries across the globe implemented using Java (JDBC,AWT,Swing) and MySQL database.
<br>
## Project Report:
doc/Report_Study_Abroad_Info_Sys.pdf
## Software Requirements:
- Java (JDK)
- MySQL (Server, Shell, Workbench)
- MySQL Java Connector
## Setup and Run:
### Executable jar file:
- Rename the '.jar' file from the java connector file to 'mysql.jar', edit environment variables and write the path to the file there
- Place it in the working directory i.e., the folder where the project code file is in
### MySQL Database setup:
- Create a studyabroad database and upload the studyabroad data file to that database
- Start the MySQL server in command prompt, using the command 'mysql -u root -p' and typing the password
### Run the program:
- Open command prompt and navigate to the current working directory and run the commands (6,7)
- Compile command: 'javac StudyAbroadInfoSystem.java'
- Run command: 'java -cp mysql.jar;. StudyAbroadInfoSystem'
- Explore the Study Abroad Information System
