# Reading Notes Class 18

- What is Amazon API Gateway? Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale. APIs act as the "front door" for applications to access data, business logic, or functionality from your backend services.
- Why is Amazon API Gateway an important part of the Serverless ecosystem? API Gateway acts as a "front door" for applications to access data, business logic, or functionality from your backend services, such as workloads running on Amazon Elastic Compute Cloud (Amazon EC2), code running on AWS Lambda, any web application, or real-time communication applications.
- How does API Gateway integrate with other AWS services? You can integrate many AWS services with API Gateway, but the setup and mapping vary based on the particular service API. To integrate another service with API Gateway, build an HTTPS request from API Gateway to the service API. This way, all request parameters are correctly mapped.

- What are the some benefits of using Amazon API Gateway? Using API Gateway, you can create RESTful APIs and WebSocket APIs that enable real-time two-way communication applications. API Gateway supports containerized and serverless workloads, as well as web applications.
- What two API types might you choose from? A public API and an internal API, for example, are two distinct types, based on who has access.

- What is DynamoDB? DynamoDB is an Amazon Web Services database system that supports data structures and key-valued cloud services. It allows users the benefit of auto-scaling, in-memory caching, backup and restore options for all their internet-scale applications using DynamoDB.
- Under what circumstances would you recommend DynamoDB over MongoDB? Looking for a database to support relatively simple key-value workloads. Heavily invested in AWS with no plans to change their deployment environment in the future.

- Explain to a non-technical friend how DynamoDB works. DyanmoDB is what organizes all of the information that you sound to a storage system like the Cloud.

- What is Dynamoose? Dynamoose is a modeling tool for Amazon's DynamoDB. Dynamoose is heavily inspired by Mongoose, which means if you are coming from Mongoose the syntax will be very familiar.
- What are some key features of Dynamoose? Type safety.
    1. High level API.
    2. Easy to use syntax.
    3. DynamoDB Single Table Design Support.
    4. Ability to transform data before saving or retrieving items.
    5. Strict data modeling (validation, required attributes, and more)
    6. Support for DynamoDB Transactions.
    7. Powerful Conditional/Filtering Support.

## Additional Information
