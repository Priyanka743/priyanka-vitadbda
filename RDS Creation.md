# Amazon RDS(Relational Database Service)

**What is amazon RDS?**

**Ans:**

*Amazon Relational Database Service (Amazon RDS) makes it easy to set up, operate, and scale a    relational database in the cloud. It provides cost-efficient and resizable capacity while managing    time-consuming database administration tasks, freeing you up to focus on your applications and    business. Amazon RDS provides you six familiar database engines to choose from, including Amazon    Aurora, PostgreSQL, MySQL, MariaDB, Oracle, and Microsoft SQL Server.*


**How to create amazon instance RDS?**

**Ans:**

*Following are the steps for creation of RDS:*

1. First open aws console.
2. Click on RDS service.
3. Choose Create database.
4. Click on mysql.
5. Select version of mysql.
6. In templates click on free tire.
7. Give instance name.
8. Give username and password, this password will be use to connect RDS to mysql.
9. Select DB instance type as db.t2 micro only.
10. In the Connectivity section, open Additional connectivity configuration and select public              accessible yes.
11. Choose Create database. Your new DB instance appears in the Databases list with the status Creating.
12. Wait for the Status of your new DB instance to show as Available. Then choose the DB instance name       to show its details.
13. In the Connectivity & security section, view the Endpoint and Port of the DB instance.


**How to conncet an instance RDS to mysql workbench?**

**Ans:**

1. In the MySQL Workbench Click on Setup new Connection,
2. Give the Connection name and Select the Connection method as Standard TCP/IP,
3. Enter the host name from RDS end point and port as 3306,
4. Enter Mysql user name and password as given in RDS instance creation,
5. Then test the connection and click ok.










