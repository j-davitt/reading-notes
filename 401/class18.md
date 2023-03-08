# Class 18 notes - API, Dynamo, and Lambda

## AWS API Gateway Overview

**What is Amazon API Gateway?**
Amazon API Gateway is a managed service that allows developers to define the HTTP endpoints of a REST API or a WebSocket API and connect those endpoints with the corresponding backend business logic. It also handles authentication, access control, monitoring, and tracing of API requests.

**Why is Amazon API Gateway an important part of the Serverless ecosystem?**
Within the Serverless ecosystem, API Gateway is the piece that ties together Serverless functions and API definitions. 

**How does API Gateway integrate with other AWS services?**
AWS Lambda: run Lambda functions to generate HTTP API responses.
AWS SNS: publish SNS notifications when an HTTP API endpoint is accessed.
Amazon Cognito: provide authentication and authorization for your HTTP APIs.

## AWS API Gateway

**What are the some benefits of using Amazon API Gateway?**
Efficient API development, easy monitoring

**What two API types might you choose from?**
RESTful and WEBSOCKET

## AWS DynamoDB Guide

**What is DynamoDB?**
DynamoDB is a hosted NoSQL database offered by Amazon Web Services (AWS)

**Under what circumstances would you recommend DynamoDB over MongoDB?**
for use with large amounts of data

## Dynamoose

**What is Dynamoose?**
Dynamoose is a modeling tool for Amazon's DynamoDB. 

**What are some key features of Dynamoose?**
- Type safety
- High level API
- Easy to use syntax
- DynamoDB Single Table Design Support
- Ability to transform data before saving or retrieving items
- Strict data modeling (validation, required attributes, and more)
- Support for DynamoDB Transactions
- Powerful Conditional/Filtering Support
- Callback & Promise support
- AWS Multi-region support
