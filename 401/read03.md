1. Name 3 real world use cases where you’d want to change the request with custom middleware

1.Auth middleware
2.Third-party Middlewares
3.Error Handing Middleware

2. True or false: The route handler is middleware?
   false

3. In what ways can a middleware function end the process and send data to the browser?

If the current middleware function does not end the request-response cycle, it must call next() to pass control to the next middleware function. Otherwise, the request will be left hanging.

4. At what point in the request lifecycle can you “inject” middleware?
   after reciveing requests

5. What can cause express to error with “Request headers sent twice, cannot start a second response”
   submitting it twice

Middleware is software that enables one or more kinds of communication or connectivity between two or more applications or application components in a distributed network. ... There are many types of middleware. Some, such as message brokers or transaction processing monitors, focus on one type of communication

The request object is the main entry point for an application to issue a request to the Library - all operations on a URL must use a Request object. The request object is application independent in that both servers and clients use the same Request class.

One of the most important objects in ASP is the Response object. It is the object which communicates between the server and the output which is sent to the client. ... DLL, parsing it so that instead of the client seeing <% Response.

Middleware in the context of distributed applications is software that provides services beyond those provided by the operating system to enable the various components of a distributed system to communicate and manage data. Middleware supports and simplifies complex distributed applications.

Routing defines the way in which the client requests are handled by the application endpoints. And when you make some routers in separate file, you can use them by using middleware.

Test-driven development (TDD) is a development technique where you must first write a test that fails before you write new functional code. TDD is being quickly adopted by agile software developers for development of application source code and is even being adopted by Agile DBAs for database development.
