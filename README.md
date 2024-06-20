# Employee-Management-System-
As part of a web-oriented project, I created an Employee Management System using J2EE, Servlets, MySQL and Java. The system has different features for Admin, Manager, and Employee positions. Admin users can do payroll for all managers and workers while taking into account the vacation and bonus holdings of each worker on an annual basis. Documents are downloaded by employees to individual managers’ directories depending on access rights given to them in this directory hierarchy managed by Super Manager that maintains assigned permissions for each document or directory within it. Organized way of assigning employees to various managers through granting them permissions associated with the latter’s own directories allows effective administrative control as well as proper handling of documents inside the organization.

## Getting Started
* Java v1.7+
* MySQL
* Spring Tools Suite

## Prerequisites
Downlaod and add the following jar in the project build path
* mysql-connector-java-5.1.40-bin.jar
* servlet-api-2.5.jar

## Run
* Select Project -> RunOnServer -> Select the exisiting server(Jetty/Pivotal) -> Select EMS-jar file -> Click Finish
* Project runs on port 8080.
* http://localhost:8080/EMS/
