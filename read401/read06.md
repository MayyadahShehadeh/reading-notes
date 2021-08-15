## Authentication

### 1. Explain what a “Singleton” is (in Computer Science terms)

A singleton is a class that allows only a single instance of itself to be created and gives access to that created instance. It contains static variables that can accommodate unique and private instances of itself. It is used in scenarios when a user wants to restrict instantiation of a class to only one object. This is helpful usually when a single object is required to coordinate actions across a system.

The singleton pattern is used in programming languages such as Java and .NET to define a global variable. A single object used across systems remains constant and needs to be defined only once rather than many times.



### 2. Explain how the Singleton pattern can be used with Node modules, specifically with classes

1. The constructor is made private. This allows only the class to have access to the singleton.

Example:
>class testdata

>{

>Private testdata ()

>{

>//… no-op for a singleton

2. A single internal instance of the class is created using a method. The method is called an instance in this example. The method “instance” is used to initialize the class to access a single instance. The instance method is marked as static in this example to give all the threads consistent access. Outside the instance creation, the “lock” statement is used to control multithreaded access. This locks the instance creation to a single thread.

Example:

> //Lazy creation of singleton internal instance

> Public static testdata Instance

> {

>Get

>{

>Lock(type of (testdata) )

>{

>If (_instance==null)

>_instance = testdata ();

>}

>Return _instance;

>}

>}

-------------------------------


### Terms:

**Router Middleware:**
The term is composed of 2 words router and middleware

Middleware:

It is a piece of code that comes in the middle of request and response. It kind of hijacks your request so that you can do anything that you want with your request or response eg: Modify the data or call the next middleware. Middleware functions are functions that have access to the request object (req), the response object (res), and the next middleware function in the application’s request-response cycle

Router:

In Express, usually, we make end-points that uses HTTP verbs to denote a GET POST DELETE PUT etc requests. Router is used to manage these incoming requests. It kind of routes your requests to correct handler/code

**Dynamic Module Loading:** Dynamic loading is a mechanism by which a computer program can, at run time, load a library (or other binary) into memory, retrieve the addresses of functions and variables contained in the library, execute those functions or access those variables, and unload the library from memory. It is one of the 3 mechanisms by which a computer program can use some other software; the other two are static linking and dynamic linking. Unlike static linking and dynamic linking, dynamic loading allows a computer program to start up in the absence of these libraries, to discover available libraries, and to potentially gain additional functionality.

**Singleton Pattern:** is a software design pattern that restricts the instantiation of a class to one "single" instance. This is useful when exactly one object is needed to coordinate actions across the system. The term comes from the mathematical concept of a singleton.


**Mock Testing:** Mock testing is an approach to unit testing that lets you make assertions about how the code under test is interacting with other system modules. In mock testing, the dependencies are replaced with objects that simulate the behaviour of the real ones. The purpose of mocking is to isolate and focus on the code being tested and not on the behaviour or state of external dependencies.