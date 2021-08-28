## AWS: Cloud Servers

### 1. Describe the Web-Request-Response-Cycle
The request/response cycle traces how a user’s request flows through the app.

 1. A user opens his browser, types in a URL, and presses Enter.
 2. When a user presses Enter, the browser makes a request for that URL.
 3. The request hits the Rails router (config/routes.rb). The router maps the URL to the correct controller and action to handle the request.
 4. The action receives the request and passes it on to the view.
 5. The view renders the page as HTML.
 6. The controller sends the HTML back to the browser. The page loads and the user sees it.

### 2. Explain what a “server” is, as it relates to the WRRC
All resources are hosted on a server. The server’s location on the web can be identified by its IP address, however, IP addresses aren’t particularly user friendly, and instead we use URLS (such as http://www.google.co.uk) to search for a resource.
Once the client’s request has reached the server, the server will search for and return the information the client is requesting. Often times, this means querying a database, loading the information into an html page, and returning the HTML text to the user in the body of the HTTP response.

### 3. What does it mean to “deploy” an application?

Application Deployment (also referred to as Software Deployment) is the process of installing, configuring, and enabling a specific application or set of applications, usually through an application manager (app manager) or software management system, to a specific URL on a server.

### Terms:

**Server:** is a piece of computer hardware or software (computer program) that provides functionality for other programs or devices, called "clients".

This architecture is called the client–server model.

Servers can provide various functionalities, often called "services", such as sharing data or resources among multiple clients, or performing computation for a client.

A single server can serve multiple clients, and a single client can use multiple servers. 

A client process may run on the same device or may connect over a network to a server on a different device Typical servers are database servers, file servers, mail servers, print servers, web servers, game servers, and application servers.

**Pub/Sub:** Pub/Sub allows services to communicate asynchronously, with latencies on the order of 100 milliseconds.

Pub/Sub is used for streaming analytics and data integration pipelines to ingest and distribute data. It is equally effective as messaging-oriented middleware for service integration or as a queue to parallelize tasks.

**WRRC:** The request/response cycle traces how a user's request flows through the app. Understanding the request/response cycle is helpful to figure out which files to edit when developing an app (and where to look when things aren't working).


