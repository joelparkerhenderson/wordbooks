# Representational State Transfer (REST)

Representational State Transfer (REST) is an architectural style for building web services. It was first introduced by Roy Fielding in his doctoral dissertation in 2000. RESTful services are built on top of the HTTP protocol, and they use standard HTTP methods like GET, POST, PUT, and DELETE to interact with resources. REST is widely used for creating web services that are scalable, flexible, and easily maintainable.

REST is based on the following principles:

* Client-Server Architecture: The client and the server are separate components that communicate with each other through a standardized interface.

* Stateless: Every request from the client to the server must contain all the necessary information required to complete the request. The server does not maintain any state about the client.

* Cacheable: Responses from the server must be cacheable or non-cacheable, depending on the requirement.

* Uniform Interface: A uniform interface should be used to interact with the resources. This interface should be simple, easy to understand, and consistent across all resources.

* Layered System: The architecture should be designed in a layered manner, with each layer having a specific role to play. This allows for scalability, flexibility, and better separation of concerns.

RESTful web services typically use the following HTTP methods:

* GET: Used to retrieve a resource or a collection of resources.

* POST: Used to create a new resource.

* PUT: Used to update an existing resource.

* DELETE: Used to delete a resource.

In addition to these methods, RESTful web services also use HTTP status codes to indicate the status of a request. For example, a status code of 200 indicates that the request was successful, while a status code of 404 indicates that the requested resource was not found.

RESTful services can be accessed by a wide range of clients, including web browsers, mobile devices, and other web services. They are widely used for building APIs that allow third-party developers to access data and functionality from a web application.