# Files-and-Indexing
The goal of this project is to implement a program that parses an ASCII text‑based CSV data file and then transforms that same information to a memory‑efficient binary format and writes it to a binary data file.



1.	language, version : Language : Java
IDE: Eclipse IDE for Java Developers Version: Luna Service Release 1a (4.4.1)

2.	File initialization :
Create a new java project with class name MyDatabase
Drag the csv file into the class file folder since I set and use the default path in this program.

3.	Operation command:
Run the program and console will display the menu of possible commands:
•	Import command: the console will indicate whether the Import command has executed, the class folder will generate data.db file and other 11 ndx file with corresponding index file.

•	Query command: type the query like SELECT FROM data.db WHERE id <= 10
There are also other arithmetic operators like “<”, “>”, “>=”, “=”,”NOT” for user to choose from , and also you can replace id with other attributes in the table.

•	Insert command : type the query like
INSERT INTO data.db VALUES (1001,AAA,aa- 111,1,11,111,11.1,TRUE,FALSE,TRUE,FALSE)
After the insert command, the program will remind the user that the insert command has finished, and user can re-run the program in query command to check if the insert command is correct.


•	Delete command : type the query like DELETE FROM data.db WHERE id = 1001
There are also other arithmetic operators like “<”, “>”, “>=”, “<=”,”NOT” for user to choose from , and also you can replace id with other attributes in the table.
After the delete command, the program will remind the user that the delete command has finished, and user can rerun the program in query command to check if the insert command is correct. 



