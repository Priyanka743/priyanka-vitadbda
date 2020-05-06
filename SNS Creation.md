# Amazon SNS(Simple Notification Service)


**What is amazon SNS?**

**Ans:**

*Amazon Simple Notification Service (Amazon SNS) is a web service that coordinates and manages the  delivery or sending of messages to subscribing endpoints or clients. In Amazon SNS, there are two types  of clients—publishers and subscribers—also referred to as producers and consumers. Publishers  communicate asynchronously with subscribers by producing and sending a message to a topic, which is a  logical access point and communication channel. Subscribers (that is, web servers, email addresses,  Amazon SQS queues, AWS Lambda functions) consume or receive the message or notification over one of the  supported protocols (that is, Amazon SQS, HTTP/S, email, SMS, Lambda) when they are subscribed to the  topic.*

**How to create SNS?**

**Ans:**

*Following are the steps for creation of SNS:*

1. Open the AWS console and click on SNS service.
2. Click on create topic.
3. Enter the topic name.
4. Enter the display name(optional)
5. Click on access policy and click on everyone.
6. Click on delivery status logging and create a new IAM roles and allow it.
7. Click on create topic.
8. Click on create subscription.
9. Select protocol e.g: mail
10. Enter endopint(email address)
11. Click on create subscription.
12. Check email id and click on mail(AWS Notification) and conform the subscription.


**How S3 connects to SNS?**

**Ans:**

*Following are the steps for connecting the S3 to SNS:*

1. Search S3 service on aws console.
2. Click on exsting bucket.
3. Click on properties.
4. Click on events.
   * Click on add notification on event.
   * Enter event name.
   * Select all object create event check box.
   * Select as SNS Topic in send to box.
   * Select SNS name.
   * Save the event.
5. Click on overview and upload file on bucket.
6. Check mail, we get mail as aws notification- File is uploded in S3 bucket.



 

















