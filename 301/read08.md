What does REST stand for?
Representational State Transfer
REST stands for Representational State Transfer. (It is sometimes spelled "ReST".) It relies on a stateless, client-server, cacheable communications protocol -- and in virtually all cases, the HTTP protocol is used. REST is an architecture style for designing networked applications.٢٢‏/٠٣‏/٢٠٠٩

REST APIs are designed around  resources____.

What is an identifer of a resource? Give an example.
A resource has an identifier, which is a URI that uniquely identifies that resource. For example, the URI for a particular customer order might be:

HTTP

Copy
https://adventure-works.com/orders/1


What are the most common HTTP verbs?
The primary or most-commonly-used HTTP verbs (or methods, as they are properly called) are POST, GET, PUT, PATCH, and DELETE. These correspond to create, read, update, and delete (or CRUD) operations, respectively. There are a number of other verbs, too, but are utilized less frequently.

What should the URIs be based on?
REST APIs use a uniform interface, which helps to decouple the client and service implementations. For REST APIs built on HTTP, the uniform interface includes using standard HTTP verbs to perform operations on resources. The most common operations are GET, POST, PUT, PATCH, and DELETE.


Give an example of a good URI.
What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
Chatty API is one that requires consumer to make tremendous (subjective matter) amount of distinct API calls to get needed information about a resource. George Reese has defined chatty API as any API that requires consumer to do more than a single call to perform a single, common operation.١٠‏/٠٨‏/٢٠١٩

What status code does a successful GET request return?
2xx Successful
This means the request was successful and the server created a new resource. ... This means the server successfully processed the request, but is not returning any content. Unlike a 204 response, this response requires that the requester reset the document view.

What status code does an unsuccessful GET request return?
If not valid, 400 Bad Request is returned. Order is processed. If the order is successful, a 201 Created is returned for the order. If an unexpected error is encountered, a 500 Server Error is returned.٢٣‏/٠٢‏/٢٠١٢

What status code does a successful POST request return?
This means the request was successful and the server created a new resource. ... This means the server successfully processed the request, but is not returning any content. Unlike a 204 response, this response requires that the requester reset the document view.

What status code does a successful DELETE request retur
Responses. If a DELETE method is successfully applied, there are several response status codes possible: A 202 ( Accepted ) status code if the action will likely succeed but has not yet been enacted. A 204 ( No Content ) status code if the action has been enacted and no further information is to be supplied.
