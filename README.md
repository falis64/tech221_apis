# API

What are API’s? How are they used and why are they so popular?
- Application Programming Interfaces (APIs) allow communication between different applications, programming languages, and platforms. It specifies how software components should interact with each other, providing a standard of access to the data and functionalities offered by an application or service. 
- API architecture is usually explained in terms of client and server. The application sending the request is called the client, and the application sending the response is called the server. So in the weather example, the bureau’s weather database is the server, and the mobile app is the client. 


Make a diagram to showcase the data transfer process in API communication.

What is a REST API? What makes an API RESTful?
- REST stands for Representational State Transfer. REST defines a set of functions like GET, PUT, DELETE, etc. that clients can use to access server data. Clients and servers exchange data using HTTP.

To be considered RESTful, an API must meet the following criteria:
- A client-server architecture comprised of clients, servers, and resources, with HTTP managing requests
- Stateless Client-server communication, which means that no client information is stored between get requests and that each request is distinct and unconnected.
- Data that can be cached to speed up client-server interactions.

What is HTTP? (what does it stand for and what is it used for?)
- Hypertext Transfer Protocol (HTTP) is a method for encoding and transporting information between a client (such as a web browser) and a web server. 

Explain HTTP request structure using the diagram provided.
- An HTTP request is made out of three components: request line, headers and message body.The request line or start line is sent by the client in order to start the action on the server. 
Explain HTTP response structure using the diagram provided.
- 

What are the 5 HTTP verbs and what do they do? GET, POST, PUT, PATCH, DELETE
- Retrieve a single item (GET)
- Retrieve a list of items (GET)
- Create an item (POST)
- Update an item (PUT)
- Delete an item (DELETE)

What is statelessness?
- Statelessness means that the servers don't save the client's data inbetween requests. This is the main feature of REST API. 

What is caching?
- The process of storing copies of files in a cache, or temporary storage location, so that they can be accessed more quickly.
