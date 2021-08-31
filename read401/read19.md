##  AWS: Events

### - Describe the similarities between AWS API Gateway + Lambda functions and an ExpressJS Server
Express is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications. With a myriad of HTTP utility methods and middleware at your disposal, creating a robust API is quick and easy. 
You can create a web API with an HTTP endpoint for your Lambda function by using Amazon API Gateway. API Gateway provides tools for creating and documenting web APIs that route HTTP requests to Lambda functions. You can secure access to your API with authentication and authorization controls. Your APIs can serve traffic over the internet or can be accessible only within your VPC.

### - What’s the difference between a FIFO and a standard queue?
Standard queues provide at-least-once delivery, which means that each message is delivered at least once. FIFO queues provide exactly-once processing, which means that each message is delivered once and remains available until a consumer processes it and deletes it.

### - How can the server be assured a message was properly received?
in the socket.io we add queue for the messages that the client didn't see yet, then when he see the messages the server will delete the message from the queue.

---------------------

### Terms: 
**Serverless API:**
Serverless is a cloud computing execution model where the cloud provider dynamically manages the allocation and provisioning of servers. A serverless application runs in stateless compute containers that are event-triggered, ephemeral (may last for one invocation), and fully managed by the cloud provider.

**Triggers:** 
A trigger is a Lambda resource or a resource in another service that you configure to invoke your function in response to lifecycle events, external requests, or on a schedule. Your function can have multiple triggers. Each trigger acts as a client invoking your function independently. Each event that Lambda passes to your function only has data from one client or trigger.

**Dynamo vs Mongo:**
The 5 Critical Differences Between DynamoDB vs MongoDB:

1. MongoDB is vendor agnostic, Open Source, and can be deployed anywhere. DynamoDB is only available on AWS.
2. DynamoDB is a fully managed AWS service, MongoDB can be self installed or fully managed with MongoDB Atlas.
3. DynamoDB as an integrated AWS service makes it easier to develop end to end solutions.
4. DynamoDB uses tables, items and attributes, MongoDB uses JSON-like documents.
5. DynamoDB supports limited data types and smaller item sizes; MongoDB supports more data types and has fewer size restrictions.