## APIs



### 1. What does REST stand for?
* proposed Representational State Transfer (REST) as an architectural approach to designing web services. REST is an architectural style for building distributed systems based on hypermedia. REST is independent of any underlying protocol and is not necessarily tied to HTTP.

### 2. REST APIs are designed around a ____.
* REST APIs are designed around resources, which are any kind of object, data, or service that can be accessed by the client.
### 3. What is an identifer of a resource? Give an example.
*An identifier of a resource is something extra built into a URI that gives extra information, an example given by the website is:
https://adventure-works.com/orders/1
### 4. What are the most common HTTP verbs?
* The most common operations, or verbs, are GET, POST, PUT, PATCH, and DELETE
### 5. What should the URIs be based on?
* These should be based on nouns (the resource) but not verbs (operations on the resource).
### 6. Give an example of a good URI.
The website has this example: https://adventure-works.com/orders // Good

https://adventure-works.com/create-order // Avoid

### 7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
* Having a "chatty" web API referrs to the abundance of requests being sent through a small number of resources. This should be avoided.
### 8. What status code does a successful GET request return?
* Status code 200 (OK)
### 9. What status code does an unsuccessful GET request return?
* Status code 404 (not found)
### 10. What status code does a successful POST request return?
* Status code 201 (created)

### 11. What status code does a successful DELETE request return?
* Status code 404 (indicating that a process has been successfully handled)