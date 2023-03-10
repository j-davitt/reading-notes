# Class 19 notes - AWS Events

## AWS SQS vs SNS

**What is the difference betweeen SQS and SNS?**
SNS is a distributed publish-subscribe service.

SQS is distributed queuing service.

**What are some use cases for both SNS and SQS?**

Choose SNS if:

You would like to be able to publish and consume batches of messages.
You would like to allow same message to be processed in multiple ways.
Multiple subscribers are needed.

Choose SQS if:

You need a simple queue with no particular additional requirements.
Decoupling two applications and allowing parallel asynchronous processing.
Only one subscriber is needed.

## AWS SNS and SQS

**Describe how to use SQS and SNS in a “fanout” pattern.**
Sending out identical messages to multiple subscribers

**Explain how “push notifications” work, using SNS.**


## SQS and SNS Basics

**How might a large scale, distributed application make use of a Queue system like SQS?**
