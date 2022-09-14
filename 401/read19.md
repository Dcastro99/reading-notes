# **AWS: Events**

> ## AWS SQS vs SNS

1. What is the difference betweeen SQS and SNS?

- `SNS` is a distributed publish-subscribe service.
- `SQS` is distributed queuing service.

2. What are some use cases for both SNS and SQS?

- `SNS` = if you would like to be able to publish and consume batches of messages.

-`SQS` = if you need a simple queue with no particular additional requirements.

> ## AWS SNS and SQS

1. Describe how to use SQS and SNS in a “fanout” pattern.

- When sending a single event to multipule endpoints, that is an `SNS` process. One of the endpoints can be an `SQS` where the event is stored and garunteed to be read by a service.

2. Explain how “push notifications” work, using SNS.

- push notifications can be handled by a lambda function. When an event occurs and that payload is sent to Lambda. The function created then auto sends and email/text as a response to the consumer. Example : when you purchase something from Amazon and then you get a thank you email.

> ## SQS and SNS Basics

1. How might a large scale, distributed application make use of a Queue system like SQS?

- Well in the example given if a hotel booking service has a sale or promotion on rooms, multiple users can login and book at the same time overloading their booking servers. An `SNS` and `SQS` and help here manage the onslought of consumers at a rate the booking servers can manage.

> ### Resources

- [SQS vs SNS](https://medium.com/awesome-cloud/aws-difference-between-sqs-and-sns-61a397bf76c5)
