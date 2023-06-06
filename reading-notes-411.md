# Reading Notes Class 16

- What is an EC2 Instance? Amazon Web Service EC2 (Amazon Elastic Compute Cloud), one of Amazon Web Services' most well-known services, offers businesses the ability to run applications on the public cloud. An EC2 instance is simply a virtual server in Amazon Web Services terminology.
- Name 2 use cases for EC2. Hosting environments. One of the foremost uses of EC2 is for hosting a variety of applications, software and websites on the cloud. Backup and disaster recovery.
- Provide 1 reason to use ECS instead of a service such as Heroku, Digital Ocean, or Render.com. There is no additional charge for Amazon ECS. You pay for AWS resources (e.g., Amazon EC2 instances or Amazon EBS volumes) you create to store and run your application. You only pay for what you use, as you use it; there are no minimum fees and no upfront commitments.

- Where can we find EC2 on the AWS Console? In the navigation pane, choose Instances.
Select the instance and choose Actions, Monitor and troubleshoot, EC2 Serial Console, Connect.
Press Enter.
- Explain the general difference between T2 Micro and XL. The capacity, cost and performance. T2 Micro costs less but its performance is not as high as XL nor is its capacity
- Explain a “Compute Cycle” to a non-technical friend. A compute cycle is the sequence of steps to: fetch a (machine language) CPU instruction (from memory or cache) decode the instruction opcode and and other sub-fields. access the operands (if any)

- What is Elastic Beanstalk? Elastic Beanstalk is a service for deploying and scaling web applications and services. Upload your code and Elastic Beanstalk automatically handles the deployment—from capacity provisioning, load balancing, and auto scaling to application health monitoring.
- Describe the relationship between EC2 and Elastic Beanstalk. Elastic Beanstalk is one layer of abstraction away from the EC2 layer. Elastic Beanstalk will setup an "environment" for you that can contain a number of EC2 instances, an optional database, as well as a few other AWS components such as a Elastic Load Balancer, Auto-Scaling Group, Security Group.
- Name some benefits of using Elastic Beanstalk. Flexible and Easy to Begin. AWS made it easy to deploy the application on AWS.
Scaling the Demand. Adjustable Auto scaling settings help Elastic Beanstalk to automatically scale the application. Control Over Tools. Provides Productivity.

## Additional Information
