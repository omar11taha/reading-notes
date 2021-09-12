<!-- from online -->
## Status Codes Based On REST Methods

1. 100 :received and the server will try to comply with a transmission demand of the client
2. 200 :doesn’t mean the request was successfully processed only that it met all validation requirements at the time of sending
3. 300 : This can have multiple reasons, be temporary or permanent, but the client has to issue a request to the new location.
4. 400 :A client is sending incorrect input and should confirm the input parameters are correct before retrying the request.
5. 500 :sometimes they can be directly related to client requests that trigger error exceptions on the server.


The status code 202 indicates that server has received and understood the request, and that it has been accepted for processing, although it may not be processed immediately. A 203 status code means that the request was received and understood, and that information sent back about the response is from a third party, rather than the original server.

A 308 Permanent Redirect message is an HTTP response status code indicating that the requested resource has been permanently moved to another URI, as indicated by the special Location header returned within the response.

GUID of the table record you want to update. A JSON object containing key: value pairs, where `key` is the property of the table and value is the value of the property you want to update. See examples later in this topic to see how you can define the data object for various update scenarios.

If the target resource does not have a current representation and the PUT successfully creates one, then the origin server MUST inform the user agent by sending a 201 (Created) response.

The 403 (Forbidden) status code indicates that the server understood the request but refuses to authorize it. A server that wishes to make public why the request has been forbidden can describe that reason in the response payload (if any).

