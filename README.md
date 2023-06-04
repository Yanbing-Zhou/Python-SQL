# Python-SQL
Using MySQL Connector and Python to implement a database on MySQL Server, and to create, read, update and delete data in that database.

## Introduction
* This is a question from: [freecodecamp](https://www.freecodecamp.org/learn/relational-database/)
* We create relational database using Python and Mysql connector, the idea is following: [Designing a Relational Database and Creating an Entity Relationship Diagram](https://towardsdatascience.com/designing-a-relational-database-and-creating-an-entity-relationship-diagram-89c1c19320b2)

## What is relational database?
According to Oracle, a relational database is “a type of database that stores and provides access to data points that are related to one another”. 

We can create, read, update and delete (the basic functions of any database) the information in our relational database using a Relational Database Management System (RDBMS). Example of RDBMSs include Oracle, Microsoft SQl Server, MySQL, and PostgreSQL, among many others. Each of these have their pros and cons (and like everything coding-adjacent, their online hyper-partisans), and SQL is not implemented in exactly the same way in each of them. The concepts are the same, but the syntax and keywords may be slightly different, so it is not usually possible to use SQL code written for PostgreSQL in Microsoft SQL Server, for example, without making some modifications.

We will be using MySQL [Community Server](https://dev.mysql.com/downloads/mysql/) because it’s free, powerful and open-source, but the others are all good choices too.

## Our target relational database:
<img src="https://miro.medium.com/v2/resize:fit:4800/format:webp/1*t3a_5INp7Xc_0u-aOK_nvg.png" alt="Alternative text" />

## Tool:
* MySQL Community Server
* MySQL Python Connector
* PopSQL
* Jupyter Notebook
* pandas
