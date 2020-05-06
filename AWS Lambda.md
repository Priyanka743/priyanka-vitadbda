# AWS Lambda


**What is AWS Lambda?**

**Ans:**

*AWS Lambda is an Amazon serverless computing system that runs code and automatically manages the  underlying computing resources. It lets a person automatically run code in response to many types of  events, such as HTTP requests from Amazon API gateway, table updates in Amazon DynamoDB, and state  transitions. It also enables the person to extend to other AWS services with custom logic, and even  create its own back-end services.*


**What are the advantages of AWS Lambda?**

**Ans:**

1. **It doesn’t require the user to manage any servers:** 
   *Since AWS Lambda automatically runs user’s code, there’s no need for the user to manage the server.     Simply write the code and upload it to Lambda.*

2. **It empowers the user to easily scale:** 
   *AWS Lambda runs code in response to each trigger, so user’s application is automatically scaled. The    code also runs in parallel processes, each triggered individually, so scaling is done precisely with     the size of the workload.*

3. **It’s affordable:**
   *With AWS Lambda, one doesn’t pay anything when code isn’t running. The user has to only be charged      for every 100ms of code execution and the number of times his code is actually triggered.*


**How to create Lambda?**

**Ans:**

1. Open AWS console and click on lambda function service.
2. Click on create function.
3. Click on use a blue print and search blueprint(means sample code) as e.g: hello or we can select       author from scratch(if we want to make code by ourself)
4. Select hello-word in language as we required
5. Click on configure.'
6. Type function name.
7. Use an existing role(which provide by aws) or we can create new roles also.
8. Click on create function.
9. Go to function code if we want to changes in given code.
10. Save the code.
11. Test the code and type the event name.(configure test event window is display as i/p of our code)
12. Click on create event.
13. Test the code.
14. Check details.




