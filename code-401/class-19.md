# AWS: Events

## AWS SQS vs SNS

1. What is the difference betweeen SQS and SNS?\
Amazon Simple Queue Service (SQS) is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications. Amazon Simple Notification Service (SNS) is a fully managed messaging service for both application-to-application (A2A) and application-to-person (A2P) communication.
2. What are some use cases for both SNS and SQS?\
Some use cases for both SNS and SQS are:\
- SNS: SNS can be used to send SMS messages to mobile device users, email recipients or even send messages to other distributed services.
- SQS: SQS can be used to decouple sending and receiving components of a distributed application. It can also be used to buffer requests in case of a sudden burst of traffic.

## AWS SNS and SQS

1. Describe how to use SQS and SNS in a “fanout” pattern.\
In a fanout pattern, a message is sent to a single queue. The queue then sends the message to multiple subscribed queues or topics. This is useful for sending the same message to multiple queues or topics. For example, you can use this pattern to send a message to multiple queues that represent different stages in a workflow. You can also use this pattern to send the same message to multiple topics that represent different endpoints for a notification. For example, you can use this pattern to send a message to multiple topics that represent different types of subscribers.
2. Explain how “push notifications” work, using SNS.\
Amazon Simple Notification Service (SNS) is a fully managed messaging service for both application-to-application (A2A) and application-to-person (A2P) communication. SNS provides a way to quickly and reliably send messages to a large number of subscribers. SNS is used for push notifications to mobile devices, distributed systems, and other services. SNS can also be used to fan out notifications to end users using mobile push, SMS, and email.

## SQS and SNS Basics

1. How might a large scale, distributed application make use of a Queue system like SQS?\
A large scale, distributed application might make use of a Queue system like SQS to decouple sending and receiving components of a distributed application. It can also be used to buffer requests in case of a sudden burst of traffic.
