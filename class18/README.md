# AWS: API, Dynamo and Lambda

### 1. What is Amazon API Gateway?
Amazon API Gateway is a fully managed service provided by Amazon Web Services (AWS) that enables developers to create, publish, maintain, monitor, and secure APIs (Application Programming Interfaces) at scale. It acts as a front-door for applications, allowing them to access data, business logic, or functionality from various back-end services or systems. 

### 2. Why is Amazon API Gateway an important part of the Serverless ecosystem?
API Gateway complements the serverless architecture by enabling developers to build serverless APIs without worrying about server provisioning, scaling, or infrastructure management. It seamlessly integrates with AWS Lambda, which allows you to implement the business logic of your APIs in stateless functions, known as Lambda functions.

### 3. How does API Gateway integrate with other AWS services?
Amazon API Gateway plays a crucial role in the serverless ecosystem by providing a secure, scalable, and easily manageable front-end for serverless applications, allowing developers to focus on building and deploying APIs without managing the underlying infrastructure.
_ _ _
### 1. What are the some benefits of using Amazon API Gateway?
- allowing your APIs to handle large numbers of concurrent requests without manual intervention.

- integrates with AWS Lambda, enabling you to build serverless applications where the business logic is implemented in stateless functions. This serverless architecture eliminates the need to manage servers, reducing operational overhead.

- API Gateway provides various security features such as access control, authentication, and authorization. 

- it offers built-in logging and monitoring capabilities. 

### 2. What two API types might you choose from?
- RESTful APIs: Representational State Transfer (REST) APIs are the most common type of APIs used in web services. They follow the REST architectural principles and use standard HTTP methods like GET, POST, PUT, DELETE...

- WebSocket APIs: WebSocket APIs enable real-time, bidirectional communication between clients and servers.
_ _ _
### 1.What is DynamoDB?
DynamoDB is a fully managed NoSQL database service provided by Amazon Web Services (AWS). It is designed to offer seamless scalability, high availability, and low-latency performance, making it well-suited for applications that require fast and consistent access to large amounts of data with varying read and write loads.

### 2. Under what circumstances would you recommend DynamoDB over MongoDB?
the choice between DynamoDB and MongoDB depends on the specific requirements of your application, the scale of your data, the desired performance characteristics, and your team's expertise with managing databases.
- For applications that demand very low read and write latencies and need to handle a high number of requests per second, DynamoDB's design for speed and performance makes it a strong candidat
- If you prefer a fully managed database service that takes care of most administrative tasks, such as backup, restore, scaling, and maintenance, DynamoDB's serverless nature 
- If you are building your application in the AWS ecosystem and want tight integration with other AWS services, DynamoDB is a natural fit as it is an integral part of AWS.
_ _ _
### 1.Explain to a non-technical friend how DynamoDB works.
 Imagine DynamoDB as a super-efficient storage system that can handle a vast amount of information . It's like having a huge bookshelf with countless drawers where you can store and retrieve data instantly.
_ _ _
### 1.What is Dynamoose?
Dynamoose is a popular JavaScript library used for working with Amazon DynamoDB, the fully managed NoSQL database service provided by Amazon Web Services (AWS). It acts as an Object-Data Mapping (ODM) library, allowing developers to interact with DynamoDB in a more familiar and intuitive way, similar to working with traditional object-oriented databases.
### 2.What are some key features of Dynamoose?
Dynamoose provides a more user-friendly and developer-friendly interface to interact with DynamoDB in Node.js applications. It simplifies data modeling, validation, querying, and other common database operations, helping developers to build robust and scalable applications with DynamoDB more efficiently.