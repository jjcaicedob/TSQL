# Introduction
New versions of two scripts included with SQL Server:
- Instpubs.sql creates the **pubs** sample database.
- Instnwnd.sql creates the **Northwind** sample database.

# Sample Files Prerequisites
The user attaching the pre-built database files must be a member of the SQL Server sysadmin or dbcreator fixed server roles.

The user running the SQL Server Sample Database Scripts must be a member of the SQL Server sysadmin or dbcreator fixed server roles, or have been granted CREATE DATABASE permissions.

The files can be used with any versions of SQL Server.

# Installing the Sample Databases
To install the sample databases

1. Either run a script to build a sample database, or attach the pre-built database files for that database.
2. To grant another person access to the sample database, you must grant permissions on the database objects to that person.

SQL Server customers can perform these tasks using the two graphical utilities SQL Query Analyzer and SQL Enterprise Manager.

Caution   Instpubs.sql drops any existing version of the pubs sample database and Instnwnd.sql drops any existing copy of the Northwind sample database before creating the new copies of the database.
