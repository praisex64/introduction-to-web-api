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