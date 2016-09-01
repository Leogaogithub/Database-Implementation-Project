# Library Mangement System by leogao
Description
This SQL programming project involves the creation of a database host application that
interfaces with a backend SQL database implementing a Library Management System. Users of
the system are understood to be librarians (not book borrowers).

Following is a brief description about the working of the system:

Search a Book - Allows the user to search any book given any combination of Book id and/or Book Title and /or Book Author. 
Checkout a Book – Allows a user to check-out the book from a branch based on its availability and book borrowers credibility. 
Checkin a Book - Allows a user to check-in the book. This feature first searches for all the book loans the borrower has taken which are not checked-in yet and then allows the user to check in the selected the book. 
Add New Borrower - Allows the user to add a new borrower to the library loan system. 
Fine - This feature allows two types of fine computation. 

how to compile, build, and install this application?
we could import this file system into eclipse. 
also we should add mysql-connector-java-5.1.38-bin.jar as referenced Libraries.
Then we could select LibraryView.java to compile and build in eclipse.
Then we could export jar by select export type as java. Runable JAR file.


It should include any technical dependencies (language, frameworks, platform, OS,
software libraries, software versions, etc.).

language: java
JavaSE-1.8
frameworks: Swing. 
platform: windows 10, Linux.
software libraries: mysql-connector-java-5.1.38-bin.jar
database: MySQL

