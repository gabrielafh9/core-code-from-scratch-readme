# From JSON to REST

## Description

Now that you know a little better what an API is, it's time to learn  
about one of the most popular ways to create an API for web applications, REST APIs.

Please answer the following questions with your own words:

#### 1. What is JSON?
    
     JSON (JavaScript Object Notation) is a lightweight data interchange format. It is a text-based, human-readable 
     format that is used to transmit data objects consisting of attribute-value pairs over a network. JSON is most 
     commonly used to exchange information between web applications and servers.
    
      - Is JSON the same as a plain Javascript object?
        
        No, JSON is not the same as a plain Javascript object. JSON is a lightweight data-interchange format which 
        is used to transfer data between server and client. It stands for JavaScript Object Notation and is based 
        on a subset of the JavaScript programming language. A plain Javascript object is an object that is created 
        directly inside a script and does not conform to the JSON syntax, for example: let obj = { name: 'Bob' };

     
#### 2. What is REST?

     REST (Representational State Transfer) is a style of software architecture that provides guidelines for creating
     scalable web services. It relies on a stateless, client-server protocol, which is both cacheable and that can make
     use of different component configurations to improve performance. RESTful web services typically utilize HTTP 
     requests to GET, PUT, POST, and DELETE data and are usually backed by a underlying database for persistence 
     and retrieval.

        - Is REST a programming language, framework, technology, or architecture pattern?
        
          REST is an architectural pattern for making distributed systems more reliable and accessible,
          used with web-based applications. It is not a programming language, framework, or technology.

   
#### 3. What is a Resource in REST?

     In REST, a resource is a remote web resource that an application connects to using an HTTP request. A resource is 
     typically a web page, a database object, or a file that is located on a server. Resources are identified by unique 
     identifiers, such as URLs or URIs. In a typical REST interaction, a client sends an HTTP request and the server uses 
     the requested resource to generate a response, usually in the form of an HTML document or image.

         - What is a resource identifier?
         
           A resource identifier is a unique alphanumeric string used to identify and locate a specific resource, 
           such as a website page, image, or file, on the internet. It is typically used in URL addresses and search engines.

   
#### 4. How are HTTP and REST related?

     HTTP and REST are closely related as REST is an architectural style for building distributed systems using web technology 
     and the HTTP protocol, which is the fundamental protocol used in the World Wide Web. HTTP is the transfer protocol used
     in REST and an integral part of the architecture.


       - What HTTP methods does REST use within its architecture rules?
      
         REST generally uses the HTTP methods GET, PUT, POST, PATCH, and DELETE.

       - Why do we use HTTP methods in REST and how do they relate to resources?
         
         HTTP methods are used in REST to interact with a resource through its representations. These methods indicate to the
         server what type of action the client wishes to perform against the resource. For example, a GET request retrieves a
         representation of the resource, a POST request creates a new resource, a PUT updates the representation of the resource 
         and a DELETE request deletes the resource.

   
#### 5. Is REST the same as HTTP?

        No, REST (Representational State Transfer) is not the same as HTTP (HyperText Transfer Protocol). REST is an architectural
        style for making requests over HTTP, which defines how resources are accessed. HTTP is a protocol that controls how data is 
        transmitted between a client and a server.

