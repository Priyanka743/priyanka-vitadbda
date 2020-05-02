**What is amazon EC2?**

**Ans**

*Amazon Elastic Compute Cloud (Amazon EC2) is a web service that provides secure, resizable compute capacity in the cloud. It allows organizations to obtain and configure virtual compute capacity in the cloud. You can select from a variety of operating systems and resource configurations like memory, CPU, storage that is required for your application. Amazon EC2 enables you to increase or decrease capacity within minutes. You can use one or hundreds or even thousands of server instances simultaneously.*

**How to create amazon EC2?**

**Ans:**

*Following are the steps of creation of EC2*

1. Open the Amazon EC2 console at https://console.aws.amazon.com/ec2/.
2. Choose Launch Instance.
3. Choose an Amazon Machine Image (AMI), find an Amazon Linux AMI at the top of the list and 
   choose select.
4. Choose an Instance Type, choose Next: Configure Instance Details.
5. Configure Instance Details.
6. Choose Next: Add Storage.
7. Choose Next: Add Tags.
8. Name your instance and choose Next: Configure Security Group.
9. Configure Security Group.
10. Choose Review and Launch.
11. Choose Launch.
12. Select the check box for the key pair that you created, and then choose Launch Instances.


**How to conncet EC2 to mobaxterm?:**

*Following are the steps of connect EC2 to mobaxterm:*

1. Start a new session by clicking on Session, then click on SSH.
2. Enter the public DNS(IP Address) from your EC2 Instance. 
3. Check the box next to "Specify username" and fill in the username as "ubuntu"
4. Click the Advanced SSH settings tab and check the box next to "Use private key" and specify the         location key pair you created when you launched your instance through the Amazon AWS website and 
   then click "OK".







