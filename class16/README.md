## AWS: Cloud Servers

1. What is an EC2 Instance?
An EC2 (Elastic Compute Cloud) instance is a virtual server in Amazon Web Services (AWS) cloud that you can use to run applications or host a website. It provides scalable computing capacity in the cloud.

2. Name 2 use cases for EC2.
* Web Hosting: EC2 instances can be used to host websites, web applications, or blogs. You can choose an appropriate instance type based on your requirements and scale your infrastructure as needed.
* Batch Processing: EC2 instances can be used for batch processing tasks such as data analysis, rendering, or encoding. You can launch multiple instances to process large amounts of data in parallel.

3. Provide 1 reason to use ECS instead of a service such as Heroku, Digital Ocean, or Render.com.
ECS allows you to manage your own infrastructure and gives you more flexibility in terms of customization and scalability.
___________________________________________________________________________________________________________
1. Where can we find EC2 on the AWS Console?
* Sign in to your AWS account.
* Open the AWS Management Console.
* In the search bar at the top, type "EC2" and select "EC2" from the suggestions.
* This will take you to the EC2 Dashboard where you can manage your EC2 instances, security groups, volumes, and other related resources.

2. Explain the general difference between T2 Micro and XL.
T2 Micro is a smaller instance type with limited CPU performance and memory, suitable for low-traffic applications or for development/testing purposes. On the other hand, XL instances offer higher CPU performance and more memory, making them suitable for applications with higher resource requirements or heavy workloads.

3. Explain a “Compute Cycle” to a non-technical friend.
A compute cycle refers to the basic unit of work performed by a computer processor. It's like a single step in solving a problem. Imagine you have a big puzzle, and you need to solve it piece by piece. Each time you put a puzzle piece in the right place, you complete one compute cycle. The more compute cycles a computer can perform per second, the faster it can solve problems or perform tasks.
___________________________________________________________________________________________________________
1. What is Elastic Beanstalk?
Elastic Beanstalk is a fully managed service provided by AWS that simplifies the deployment and management of applications. It automates the process of setting up the underlying infrastructure, such as EC2 instances, load balancers, and databases, allowing developers to focus on writing code rather than worrying about infrastructure configuration.

2. Describe the relationship between EC2 and Elastic Beanstalk.
When you deploy an application using Elastic Beanstalk, it automatically provisions and manages the necessary EC2 instances and other AWS resources required to run your application.

3. Name some benefits of using Elastic Beanstalk.
* Easy Application Deployment.
* Auto Scaling: Elastic Beanstalk can automatically scale your application based on the configured settings.
* Monitoring and Health Management.
* Platform Support: Elastic Beanstalk supports multiple programming languages and platforms.
