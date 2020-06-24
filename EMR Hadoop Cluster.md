# Big Data


**Que:How To Create Hadoop Cluster With Amazon EMR?**

**Ans:**

*Following are the steps to creation of hadoop cluser:*

1. First open aws console.
2. Then click on EMR management console.
3. Click on create cluster.
4. Give the name of the cluster.
5. Uncheck the logging box option
6. Select the instance type as m4.large
7. Select the number of instances.
8. Select the key pair.
6. Click on create cluster.
7. Then once cluster created, 
8. Click on summary and then click on master security group and add the SSH 
   rules in inbound rule.
9. Click on hardware and copy the public ip address to connect to SSH.
10. Finally EMR hadoop cluster connects to SSH.



