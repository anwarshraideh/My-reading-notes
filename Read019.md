# Readings: AWS: Events

## Review, Research, and Discussion

- Describe the similarities between AWS API Gateway + Lambda functions and an ExpressJS Server .
Amazon’s API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale
Express Gateway is an API Gateway that can sit at the heart of any microservices architecture, regardless of what language or platform you’re using. Express Gateway secures your microservices and exposes them through APIs using Node.js, ExpressJS and Express middleware.

- What’s the difference between a FIFO and a standard queue?
FIFO queues have essentially the same features as standard queues, but provide the added benefits of supporting ordering and exactly-once processing and ensure the order in which messages are sent and received is strictly preserved
- How can the server be assured a message was properly received?
By having the client emit a “received” event back to the server upon receipt of the message


## Term

- Serverless API : Serverless is a cloud computing execution model where the cloud provider dynamically manages the allocation and provisioning of servers. A serverless application runs in stateless compute containers that are event-triggered, ephemeral (may last for one invocation), and fully managed by the cloud provider.


- Triggers : an AWS Lambda resource or resource in another service that you configure to invoke your function in response to lifecycle events, external requests or on a schedule, a function can have multiple triggers

- Dynamo vs Mongo : 
MongoDB is vendor agnostic, Open Source, and can be deployed anywhere. DynamoDB is only available on AWS. DynamoDB is a fully managed AWS service, MongoDB can be self installed or fully managed with MongoDB Atlas. DynamoDB as an integrated AWS service makes it easier to develop end to end solutions. DynamoDB uses tables, items and attributes, MongoDB uses JSON-like documents. DynamoDB supports limited data types and smaller item sizes; MongoDB supports more data types and has fewer size restrictions.


- Dynamoose vs Mongoose : Dynamoose is a DynamoDB API structured like Mongoose, lets us provide a schema and perform CRUD operations against a DynamoDB table, installed via node and configured based on role


## Preparation Materials

 ***AWS SQS***

Amazon Simple Queue Service (Amazon SQS) is a reliable, highly-scalable hosted queue for storing messages as they travel between applications or microservices. Amazon SQS moves data between distributed application components and helps you decouple these components.

For information on the permissions you need to use this API, see Identity and access management in the Amazon Simple Queue Service Developer Guide.

You can use AWS SDKs to access Amazon SQS using your favorite programming language. The SDKs perform tasks such as the following automatically:

Cryptographically sign your service requests

Retry requests

Handle error responses 

***SNS***

Simple Notification Service
Fast, flexible, and fully managed push notification service that lets you send individual messages or bulk messages
Distributed publish/subscribe system
Messages are pushed to subscribers as and when they are sent by publishers to SNS
SNS supports several end points such as email, SMS, HTTP endpoint, and SQS
If you want an unknown number and type of subscribers to receive messages, you need SNS
