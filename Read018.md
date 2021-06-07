
# Readings: AWS: API, Dynamo and Lambda

# Review, Research, and Discussion

- What are serverless functions? 

 are single-purpose, programmatic functions that are hosted on managed infrastructure. These functions, which are invoked through the Internet, are hosted and maintained by cloud computing companies.

- If you were to create a system that emulated Lambda functions, how would you do it?
To create a Lambda function with the console

Open the Functions page on the Lambda console.

Choose Create function.

Under Basic information, do the following:

For Function name, enter my-function.

For Runtime, confirm that Node.js 14.x is selected. Note that Lambda provides runtimes for .NET (PowerShell,C#) Go, Java, Node.js, Python, and Ruby.

Choose Create function.

Lambda creates a Node.js function and an execution role that grants the function permission to upload logs. The Lambda function assumes the execution role when you invoke your function, and uses the execution role to create credentials for the AWS SDK and to read data from event sources.

- Describe how a CDN works .
CDNs store a cached version of your website content in multiple geographical locations around the world, which are known as “points of presence” (PoPs). These PoPs will contain their own caching servers and will be responsible for delivering that content in the user’s location.

# Term

- ***Serverless Functions*** is a programmatic function written by a software developer for a single purpose. It's then hosted and maintained on infrastructure by cloud computing companies. These companies take care of code maintenance and execution so that developers can deploy new code faster and easier.

- ***Cloud Storage*** is a model of computer data storage in which the digital data is stored in logical pools, said to be on “the cloud”. The physical storage spans multiple servers (sometimes in multiple locations), and the physical environment is typically owned and managed by a hosting company. These cloud storage providers are responsible for keeping the data available and accessible, and the physical environment protected and running. People and organizations buy or lease storage capacity from the providers to store user, organization, or application data.

- ***CDN*** is a highly-distributed platform of servers that helps minimize delays in loading web page content by reducing the physical distance between the server and the user. This helps users around the world view the same high-quality content without slow loading times.


# Preparation Materials

Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale. Using API Gateway, you can create RESTful APIs and WebSocket APIs that enable real-time two-way communication applications.

API Gateway sits between the backend services of your API and your API’s users, handling the HTTP requests to your API endpoints and routing them to the correct backends. It provides a set of tools that help you manage your API definitions and the mappings between endpoints and their respective backend services. It can also generate API references from your definitions and make them available to your users as API documentation.

DynamoDB is a hosted NoSQL database offered by Amazon Web Services (AWS). It offers: reliable performance even as it scales; a managed experience, so you won’t be SSH-ing into servers to upgrade the crypto libraries; a small, simple API allowing for simple key-value access as well as more advanced query patterns.

Dynamoose is a modeling tool for Amazon’s DynamoDB. Dynamoose is heavily inspired by Mongoose, which means if you are coming from Mongoose the syntax will be very familar.
