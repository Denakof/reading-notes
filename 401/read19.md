Describe the similarities between AWS API Gateway + Lambda functions and an ExpressJS Server


An API Gateway is “middleware” that makes available backend services to mobile, web and other external clients via a set of protocols and commonly through a set of RESTful application programming interfaces (APIs). An API Gateway makes it much simpler to develop, secure, manage, and scale endpoints by moving most of the required logic from the client, into the gateway.

Express Gateway is an API Gateway that can sit at the heart of any microservices architecture, regardless of what language or platform you’re using. Express Gateway secures your microservices and exposes them through APIs using Node.js, ExpressJS and Express middleware.

Amazon’s API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale. With a few clicks you can create an API that acts as a “front door” for applications to access data, business logic, or functionality from your back-end services, such as workloads running on Amazon Elastic Compute Cloud (Amazon EC2), code running on AWS Lambda, or any Web application. Amazon API Gateway handles all the tasks involved in accepting and processing up to hundreds of thousands of concurrent API calls, including traffic management, authorization and access control, monitoring, and API version management.


List the AWS Database offerings and talk about the pros and cons of each

RDS is one of the most popular services in AWS boasting a wide array of customers seeking to reduce dependency on their DBAs and enabling their existing staff to operate more databases than they were able to previously. AWS teams manage the provisioning of the infrastructure and performing maintenance tasks on the RDS instance. Administration processes such as patching the RDS database, backup of databases and point-in-time recovery are automated. A single API

What’s the difference between a FIFO and a standard queue?
Standard queues guarantee that a message is delivered at least once and duplicates can be introduced into the queue. FIFO queues ensure a message is delivered exactly once and remains available until a consumer processes and deletes it; duplicates are not introduced into the queue.

How can the server be assured a message was properly received?
to get a response from the client that the message was received

Serverless:
Serverless is a cloud computing execution model where the cloud provider dynamically manages the allocation and provisioning of servers hackernoon (Links to an external site.)

Triggers

Triggers are stored programs, which are automatically executed or fired when some events occur.

Dynamo vs Mongo(1) DynamoDB is a fully managed AWS service, MongoDB can be self installed or fully managed with MongoDB Atlas.(2) DynamoDB uses tables, items and attributes, MongoDB uses JSON-like documents. (3) DynamoDB supports limited data types and smaller item sizes; MongoDB supports more data types and has fewer size restrictions.

Dynamoose vs Mongoose
Both are modeling/schema tools for their corrosponding databases (Dynamo and Mongo). Dynamoose is heavily inspired by Mongoose
