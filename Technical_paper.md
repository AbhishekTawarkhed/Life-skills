# Technical Paper: REST Architecture

Representational State Transfer (REST) is an architectural style introduced by Roy Fielding in 2000 for designing distributed systems, particularly web-based APIs. REST is not a protocol but a set of constraints that guide how resources should be defined and accessed over the web. A RESTful system identifies resources using Uniform Resource Identifiers (URIs) and interacts with them through standard HTTP methods such as GET, POST, PUT, and DELETE. These methods map directly to CRUD operations: Create, Read, Update, and Delete. REST emphasizes stateless communication, meaning each request from a client to a server must contain all the necessary information, without relying on stored context. Another key principle is the uniform interface, which ensures consistency in how clients interact with resources. REST also supports layered architecture, allowing intermediaries such as proxies or gateways to improve scalability and performance. By adhering to these constraints, RESTful APIs achieve simplicity, scalability, and flexibility, making them the backbone of modern web services.

## Key Points
* REST is an architectural style, not a protocol.
* Resources are identified using URIs.
* HTTP methods map to CRUD operations.
* Stateless communication ensures scalability.
* Uniform interface provides consistency.
* Layered architecture improves performance.

## References
* [The REST Architecture - Baeldung](https://www.baeldung.com/cs/rest-architecture)
* [REST API Introduction - GeeksforGeeks](https://www.geeksforgeeks.org/rest-api-introduction/)
* [REST API Tutorial - REST Explained](https://restfulapi.net/)
* [Roy Fielding’s Dissertation on REST](https://www.ics.uci.edu/~fielding/pubs/dissertation/rest_arch_style.htm)
