# 3NF_to_Datawarehouse
The goal of this project is to convert a business process database that is in 3NF into a datawarehouse that is ready for  analytics operations.
### What is 3NF? 
A relation is in third normal form, if there is no transitive dependency for non-prime attributes as well as it is in second normal form. To read more about Normal forms <a href="https://www.geeksforgeeks.org/normal-forms-in-dbms/">click here</a>
<h4> About the Database</h4>
The Pagila database is the Postgresql version of the Sakila database that was designed by Mike Hillyer, a former member of the MySQL AB documentation team. It is intended to provide a standard schema. The Pagila Database is a sample database that can be used to learn and practice POSTGRESQL. The Database represents the business process of a film rental store. It consists of:<br/>
- 15 tables
- 1 trigger
- 7 views
- 8 functions
- 1 domain
- 13 sequences 
<h4> Schema of the Pagila database</h4>
<img src ="images/pagila-3nf.png"><br/>
<a href="https://github.com/devrimgunduz/pagila.git"> Download the script of the pagila database here</a>

This repository consist of a folder and two files.
The folder contains images of the pagila sample database used and the datawarehouse Schema we will be working on.
- file Workspace.ipynb is a jupyter notebook that explains the step by step process of achieving this task.
- Readme.md

#### The GOAL
##### Star Schema - Entity Relationship Diagram
<img src="images/pagila-star.png" width="50%"/>
