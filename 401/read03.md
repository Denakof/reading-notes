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
