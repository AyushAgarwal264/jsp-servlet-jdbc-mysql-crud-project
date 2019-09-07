# jsp-servlet-jdbc-mysql-crud-project
JSP Servlet JDBC MySQL CRUD User Management
JAVA based with back-end controlled by JDBC. 
Database Used: MySql
JDBC (Java Database Connectivity) is uses for connect java application with database. It is Java SE technology, which is installed automatically with the jdk software. Jdbc is an API (Application programming interface) used to communicate Java application to database in database independent and platform independent manner. It provides classes and interfaces to connect or communicate Java application with database.
Tools and technologies used
•	JSP - 2.2 +
•	IDE - STS/Eclipse Neon.3
•	JDK - 1.8 or later
•	Apache Tomcat - 8.5
•	JSTL - 1.2.1
•	Servlet API - 2.5
•	MySQL - mysql-connector-java-8.0.13.jar
Development Steps
1.	Create an Eclipse Dynamic Web Project
2.	Add Dependencies
3.	Project Structure
4.	MySQL Database Setup
5.	Create a JavaBean - User.java
6.	Create a UserDAO.java
7.	Create a UserServlet.java
8.	Creating User Listing JSP Page - user-list.jsp
9.	Create a User Form JSP Page - user-form.jsp
10.	Creating Error JSP page
11.	Deploying and Testing the Application Demo
1. Create an Eclipse Dynamic Web Project
To create a new dynamic Web project in Eclipse:
1. On the main menu select File > New > Project....
2. In the upcoming wizard choose Web > Dynamic Web Project.
 
3. Click Next.
4. Enter project name as "jsp-servlet-jdbc-mysql-example";
5. Make sure that the target runtime is set to Apache Tomcat with the currently supported version. 
2. Add Dependencies
Add the latest release of below jar files to the lib folder.
•	jsp-api.2.3.1.jar
•	servlet-api.2.3.jar
•	mysql-connector-java-8.0.13.jar
•	jstl-1.2.jar
3. Project Structure
Standard project structure for your reference - 
 

