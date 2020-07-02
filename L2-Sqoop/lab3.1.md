# Lab2: Importing RDBMS Data into HDFS


**Objective: Import data from a database into HDFS**

*Following are the steps for importing RDBMS data into HDFS:*

1. Open aws console and create an amazon RDS.

2. Connect this database to MySql workbench and make sure your database connect to workbench.

3. Create salaries table in connected database as follow:

	create table salaries(
        gender varchar(1),
        age int,
        salary double,
        zipcode int);

4. Load salaries.txt file data into this salaries table by using following command:
	
	load data local infile 'file path/salaries.txt' into table salaries fields terminated by ','

	If you get an infile error while inserting the data then perform following steps:

	  *  Close current SQL connection
	  *  Right click on your Connection and select 'Edit Connection'
	  *  Click on Advanced
 	  *  Add following line to 'Others'

    		 OPT_LOCAL_INFILE=1

	  *  Now Reconnect to your database 

5. Create EMR cluster and connect it with SSH.

6. Run sqoop import command to import data from sql database to hdfs.
	
![Sqimport](../images/L1.jpg)

7. Now check whether salaries directory is created on hdfs as follow:
	
![dirch](https://github.com/Priyanka743/priyanka-vitadbda/tree/Big-Data/images/L2.jpg)

8. Then use cat command to see the data in the file.

![dirdata](https://github.com/Priyanka743/priyanka-vitadbda/tree/Big-Data/images/L3.jpg)

9. Now we will import only salary and age data from the database and put it into new directory named salaries2.
 	
![dirdata1](https://github.com/Priyanka743/priyanka-vitadbda/tree/Big-Data/images/L4.jpg)

10. Now check whether salaries2 directory is created on hdfs with 2 files present as shown below:
	
![dirdata2](https://github.com/Priyanka743/priyanka-vitadbda/tree/Big-Data/images/L5.jpg)

11. Then use cat command to see the data in the file.

![dirdata2](https://github.com/Priyanka743/priyanka-vitadbda/tree/Big-Data/images/L6.jpg)

12. Now we will use --split-by command to split our data according to a certain column value and put it into new directory named salaries3.

![dirdata3](https://github.com/Priyanka743/priyanka-vitadbda/tree/Big-Data/images/L7.jpg)

13. Now check whether salaries3 directory is created on hdfs with 3 files present as shown below:
      
![dirdata4](https://github.com/Priyanka743/priyanka-vitadbda/tree/Big-Data/images/L8.jpg)

14. Then use cat command to see the data in the file.
	
![dirdata4](https://github.com/Priyanka743/priyanka-vitadbda/tree/Big-Data/images/L9.jpg)

	

  






	

	
