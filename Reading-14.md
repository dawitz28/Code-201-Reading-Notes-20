
# Reading notes 14 #
## Introduction to Database Normalization ##
-	Database Normalization:- is a way of rearranging the database information into tables and columns. The most important about this is that a table is all about a specific topic and only supporting topics are included. 
-	when we focus our table purpose to one topic we limit the number of duplicate data contained within our database and that will lead to avoiding some issues that might come from database modifications. 
-	There are three main reasons to normalize a database.
o	Minimize duplicate data.
o	Minimize or avoid data modification issues.
o	Simplify queries. 
-	Data Duplication and Modification Anomalies:- When you have common information within the company that co-workers share like company address, phone number and office number this duplicated information can bring two problems.
o	We can have an increases storage and decrease performance. 
o	We can have a hard time to maintain data changes. 
-	Whenever we run into these sort of situation where we have to update very large database information is called modification anomalies and Database normalization can fix them. 
-	There are three modification anomalies that can occur:-
o	Insert Anomaly
o	Update Anomaly
o	Deletion Anomaly

