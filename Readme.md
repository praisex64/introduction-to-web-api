# INTRODUCTION TO WEB API

## What is An API

API or application programming interface enable different software systems to interact with each other by defining a standard way for them to exchange data and functionality. They act as intermediaries between software applications, allowing them to communicate with each other without requiring the developers to know the internal workings of each other's systems.

APIs are typically used to enable communication between web-based applications, but they can also be used for other types of software. For example, an API could allow a mobile application to interact with a cloud-based database or an Internet of Things (IoT) device to send and receive data from a server.

In essence, an API defines a set of rules for how software applications should communicate with each other, including the format and structure of the data that is exchanged, the types of requests that can be made, and the responses that will be provided. By providing a standard way for software applications to interact with each other, APIs make it easier for developers to build complex systems that are composed of multiple interconnected components.


## What does API stands for?
Application Programming Interface is referred to as API. Any software with a specific function is referred to as an application when discussing APIs. Interface can be compared to a service agreement between two programs. This agreement specifies the requests and responses that the two parties will use to communicate. Developers can find instructions in their API documentation on how to format those requests and responses.

## How do APIs work?
Client and server architecture is typically defined in terms of APIs. Applications that transmit requests and responses are referred to as clients and servers, respectively. In the weather example, the mobile app is the client and the bureau's weather database is the server. 

APIs can function in four ways, depending on when and why they were created.

SOAP APIs:
SOAP stands for Simple Object Access Protocol.
These APIs use Simple Object Access Protocol. Client and server exchange messages using XML. This is a less flexible API that was more popular in the past.

RPC APIs
RPC stands for Remote Procedure Calls.
These APIs are called Remote Procedure Calls. The client completes a function (or procedure) on the server, and the server sends the output back to the client.

Websocket APIs
Websocket API is another modern web API development that uses JSON objects to pass data. A WebSocket API supports two-way communication between client apps and the server. The server can send callback messages to connected clients, making it more efficient than REST API.

REST APIs
REST stands for Representational State Transfer.
These are the most popular and flexible APIs found on the web today. The client sends requests to the server as data. The server uses this client input to start internal functions and returns output data back to the client.

REST APIs in more detail below.
Representational State Transfer is referred to as REST. For clients to access server data, REST defines a set of functions including GET, PUT, DELETE, etc. Using HTTP, clients and servers exchange data.

The main feature of REST API is statelessness. Statelessness means that servers do not save client data between requests. Client requests to the server are similar to URLs you type in your browser to visit a website. The response from the server is plain data, without the typical graphical rendering of a web page.

## What are the benefits of REST APIs?

REST APIs offer four main benefits:
1. Integration 
APIs are used to integrate new applications with existing software systems. This increases development speed because each functionality doesn’t have to be written from scratch. You can use APIs to leverage existing code.

2. Innovation
Entire industries can change with the arrival of a new app. Businesses need to respond quickly and support the rapid deployment of innovative services. They can do this by making changes at the API level without having to re-write the whole code.

3. Expansion
APIs present a unique opportunity for businesses to meet their clients’ needs across different platforms. For example, maps API allows map information integration via websites, Android,iOS, etc. Any business can give similar access to their internal databases by using free or paid APIs.

4. Ease of maintenance
The API acts as a gateway between two systems. Each system is obliged to make internal changes so that the API is not impacted. This way, any future code changes by one party do not impact the other party.

## What are the different types of APIs?
APIs are classified both according to their architecture and scope of use.

### Private APIs
These are internal to an enterprise and only used for connecting systems and data within the business.

### Public APIs 
These are open to the public and may be used by anyone. There may or not be some authorization and cost associated with these types of APIs.

### Partner APIs 
These are only accessible by authorized external developers to aid business-to-business partnerships.

### Composite APIs
These combine two or more different APIs to address complex system requirements or behaviors. 

## How to secure a REST API?
Through adequate authentication and monitoring, all APIs must be secured. There are two primary methods for protecting REST APIs:

1. Authentication tokens
These are used to provide users permission to perform API calls. Authentication tokens verify that the users are who they say they are and that they have permission to make that particular API call. When you connect in to your email server, for example, your email client uses authentication tokens to provide secure access.

2. API keys
API keys authenticate the software or application that is making the API call. They identify the program and ensure it has the necessary access rights to make the API call. API keys are not as secure as tokens, but they do allow API monitoring to collect usage data. When you visit different websites, you may have observed a long string of characters and numbers in your browser URL. This string serves as an API key for the website's internal API calls.

## What is web API?
A Web API, also known as a Web Service API, is an application processing interface that connects a web server and a web browser. APIs are all web services, but not all web services are APIs. 

REST API is a form of Web API that follows the standard architectural style described above.