# Amazon RDS(Relational Database Service)

**What is amazon RDS?**

**Ans:**

*Amazon Relational Database Service (Amazon RDS) makes it easy to set up, operate, and scale a   relational database in the cloud. It provides cost-efficient and resizable capacity while managing   time-consuming database administration tasks, freeing you up to focus on your applications and   business. Amazon RDS provides you six familiar database engines to choose from, including Amazon   Aurora, PostgreSQL, MySQL, MariaDB, Oracle, and Microsoft SQL Server.*


**How to create amazon RDS?**

**Ans:**

*Following are the steps for creation of RDS:*

1. First open aws console and then go to the RDS console.
2. In the upper-right corner of the AWS Management Console, choose the AWS Region in which you want to      create the DB instance. This example uses the US West (Oregon) Region.
3. In the navigation pane, choose Databases.
4. Choose Create database.
5. On the Create database page, shown following, make sure that the Standard Create option is chosen,       and then choose MySQL.
6. In the Templates section, choose Dev/Test.
7. In the Settings section, set these values:
	* DB instance identifier – tutorial-db-instance
	* Master username – tutorial_user
	* Auto generate a password – Disable the optionMaster password – Choose a password.
	* Confirm password – Retype
8. In the DB instance size section, set these values:
	* DB instance performance type – Burstable
	* DB instance class – db.t2.small the password.
9. In the Storage and Availability & durability sections, use the default values.
10. In the Connectivity section, open Additional connectivity configuration and set these values:
	* Virtual Private Cloud (VPC) – Choose an existing VPC with both public and private subnets, 	           such as the tutorial-vpc (vpc-identifier) created in Create a VPC with Private and Public 	           Subnets.	
	* Subnet group – The DB subnet group for the VPC, such as the tutorial-db-subnet-group created 	  in Create a DB Subnet Group
	* Publicly accessible – No
	* VPC security groups – Choose an existing VPC security group that is configured for private 	           access, such as the tutorial-db-securitygroup created in Create a VPC Security Group for a 	  	  Private DB Instance. Remove other security groups, such as the default security group, by                choosing the X associated with each.
	* Availability zone – No Preference
	* Database port – 3306
11. Open the Additional configuration section, and enter sample for Initial database name. Keep the          default settings for the other options.
12. To create your Amazon RDS MySQL DB instance, choose Create database. Your new DB instance appears in     the Databases list with the status Creating.
13. Wait for the Status of your new DB instance to show as Available. Then choose the DB instance name       to show its details
14. In the Connectivity & security section, view the Endpoint and Port of the DB instance.


**How to conncet RDS to mysql workbench?**

**Ans:**

1. In the MySQL Workbench Click on Setup new Connection,
2. Give the Connection name and Select the Connection method as Standard TCP/IP,
3. Enter the host name from RDS end point and port as 3306,
4. Enter Mysql user name and password as given in RDS instance creation,
5. Then test the connection and click ok.


*I have refered above contents from AWS site:*

[https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/CHAP_Tutorials.WebServerDB.CreateDBInstance.html]







