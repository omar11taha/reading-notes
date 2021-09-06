<!-- from online -->
## REST
1. What does REST stand for?
REST is acronym for REpresentational State Transfer. It is architectural style for distributed hypermedia systems and was first presented by Roy Fielding in 2000 in his famous dissertation.

2. REST APIs are designed around a ?
REST or RESTful API design (Representational State Transfer) is designed to take advantage of existing protocols. While REST can be used over nearly any protocol, it usually takes advantage of HTTP when used for Web APIs. ... REST API Design was defined by Dr. Roy Fielding in his 2000 doctorate dissertation.

3. What is an identifer of a resource? 
The essence of the merge comes down to answering the question “When is a node in one graph the same node as a node in another graph?” In RDF, this issue is resolved through the use of Uniform Resource Identifiers (URIs).

4. What are the most common HTTP verbs?
The primary or most-commonly-used HTTP verbs (or methods, as they are properly called) are POST, GET, PUT, PATCH, and DELETE. These correspond to create, read, update, and delete (or CRUD) operations, respectively. There are a number of other verbs, too, but are utilized less frequently.

5. What should the URIs be based on?
A Uniform Resource Identifier (URI) is a unique sequence of characters that identifies a logical or physical resource used by web technologies.

6. Give an example of a good URI.
 ![URL](https://thenewtechnicalwriter.files.wordpress.com/2015/07/uri.png)

7. What does it mean to have a ‘chatty’ web API? 
Chatty API is one that requires consumer to make tremendous (subjective matter) amount of distinct API calls to get needed information about a resource. George Reese has defined chatty API as any API that requires consumer to do more than a single call to perform a single, common operation.

8. What status code does a successful GET request return?
Generally, this means that the server provided the requested page. ... This means the server successfully processed the request, but is not returning any content. Unlike a 204 response, this response requires that the requester reset the document view.

9.What status code does an unsuccessful GET request return?
If not valid, 400 Bad Request is returned. Order is processed. If the order is successful, a 201 Created is returned for the order. If an unexpected error is encountered, a 500 Server Error is returned.

10. What status code does a successful POST request return?
This means the request was successful and the server created a new resource. ... This means the server successfully processed the request, but is not returning any content. Unlike a 204 response, this response requires that the requester reset the document view.

11. What status code does a successful DELETE request return?
A successful response of DELETE requests SHOULD be HTTP response code 200 (OK) if the response includes an entity describing the status, 202 (Accepted) if the action has been queued, or 204 (No Content) if the action has been performed but the response does not include an entity