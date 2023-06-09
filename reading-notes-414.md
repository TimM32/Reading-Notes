# Reading Notes Class 19

- What is the difference betweeen SQS and SNS? SNS is a pub/sub system, while SQS is a queueing system. You'd typically use SNS to send the same message to multiple consumers via topics. In comparison, in most scenarios, each message in an SQS queue is processed by only one consumer.
- What are some use cases for both SNS and SQS?
    1. SNS is typically used for applications that need realtime notifications, while SQS is more suited for message processing use cases.
    2. One common use case for SQS and SNS is to build a serverless event-driven architecture, where events trigger the execution of code in AWS Lambda.
    3. A typical example would be a Fanout scenario which requires asynchronous processing of messages.

- Describe how to use SQS and SNS in a “fanout” pattern. A "fanout" pattern, messages are sent to a single SNS topic, and multiple SQS queues are subscribed to that topic. Each queue receives a copy of the message, allowing for parallel processing and distribution of messages to multiple consumers or workers.
- Explain how “push notifications” work, using SNS. Push notifications are on-screen clickable alerts delivered by an app or website to users on their desktops, laptops, or mobiles. They contain snippets of information meant to be sent by brands to a user's device.

- How might a large scale, distributed application make use of a Queue system like SQS?
    1. Separate Throughput from Latency
    2. Use Batch APIs Wherever Relevant
    3. Tradeoff Message Durability and Latency

## Additional Information
