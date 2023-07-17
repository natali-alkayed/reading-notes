# S3 and Lambda

1. What is Amazon S3?
Amazon S3 (Simple Storage Service) is a cloud-based object storage service provided by Amazon Web Services (AWS). It is designed to store and retrieve any amount of data at any time, making it highly scalable and reliable for various use cases.

2. Name some use cases for Amazon S3.
- Data backup and archiving.
- Web hosting and static website hosting.
- Big data analytics.
- Application data storage.

3. Name some benefits of using Amazon S3.
Amazon S3 is a (versatile and reliable) storage service that can meet the needs of diverse applications and use cases while (offering strong data protection and cost efficiency).
___________________________________________________________________________________________________________

1. What is AWS Lambda?
AWS Lambda is a serverless computing service provided by Amazon Web Services (AWS). It allows developers to run code without managing servers directly. Instead of provisioning and maintaining servers, developers only need to upload their code to AWS Lambda, and the service takes care of everything required to execute the code.

2. Name some use cases for AWS Lambdas.
- Event-driven processing.
- Real-time file processing.
- IoT (Internet of Things) applications
- Chatbots and voice assistants.

3. Describe “serverless” to a non-technical friend.
Imagine you have a magical assistant that can complete tasks for you without you needing to worry about how they are done. This assistant can do things like organizing your files, translating languages, or even cooking recipes. All you have to do is tell the assistant what you need, and it will handle everything for you.

AWS Lambda is like that magical assistant for computer programs. When developers create software, they usually need to think about where and how to run it on servers. But with AWS Lambda, they don't have to worry about servers at all. They can just focus on writing the code to solve a specific problem, and AWS Lambda takes care of running that code for them.

It's called "serverless" because, even though the code needs a server to run, developers don't have to manage the servers themselves. They don't need to think about how many servers are needed, how to keep them updated, or how to make sure they are always available. AWS Lambda handles all of that behind the scenes, making it much simpler and faster for developers to build and deploy their applications. So, in a way, it's like having a server without actually worrying about the server!
___________________________________________________________________________________________________________

1. What is a CDN?
CDN stands for Content Delivery Network. It is a distributed network of servers strategically placed in various locations around the world to deliver web content, such as images, videos, stylesheets, scripts, and other assets, to users more efficiently and reliably.

2. How does a CDN work with relation to the website visitor?
- Content caching: When a user visits a website that uses a CDN, the CDN server closest to the user's geographic location will cache and store copies of the website's static content. This content includes images, CSS files, JavaScript files, and other resources.

- Reduced latency: When the user requests a page from the website, the CDN will serve the cached content from the nearest server instead of the original web server where the website is hosted. This reduces the physical distance the data needs to travel, leading to lower latency and faster loading times.

- Load distribution: CDNs distribute the load across multiple servers, preventing any single server from being overwhelmed with traffic. This load balancing helps maintain consistent performance during high traffic periods and prevents server crashes.

- Dynamic content optimization: While CDNs are primarily used for caching static content, some advanced CDNs can also optimize and cache certain dynamic content, like personalized pages or frequently accessed API responses, to further improve performance.

- Global availability: CDNs have servers located in multiple regions worldwide, ensuring that content is readily available to users regardless of their location. This global presence helps reduce the impact of internet congestion and outages in specific regions.

3. What are the benefits of employing a CDN?
- Faster website loading times.
- Improved website performance.
- Better scalability.
- Enhanced reliability.
- Cost savings and Global reach.