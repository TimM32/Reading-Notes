# Reading Notes Class 308

- What does REST stand for? Representational State Transfer (REST) is a software architecture that imposes conditions on how an API should work. REST was initially created as a guideline to manage communication on a complex network like the internet.
- REST APIs are designed around a ____. resources.
- What is an identifier of a resource? Give an example. A Uniform Resource Identifier (URI) is a character sequence that identifies a logical (abstract) or physical resource and an example is foo://example.com:8042/over/there?name=ferret#nose
- What are the most common HTTP verbs? The primary or most-commonly-used HTTP verbs (or methods, as they are properly called) are POST, GET, PUT, PATCH, and DELETE. These correspond to create, read, update, and delete (or CRUD) operations, respectively.
- What should the URIs be based on? 
- Give an example of a good URI.URLs always need to be clear, unambiguous, easy to read, easy to type and easy to share. all URLs must be in lower case. URLs must use words and should not contain acronyms, wherever possible (see 8 for an exception where acronyms are used for an organisation redirect)
- What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing? Chatty API is one that requires consumer to make tremendous (subjective matter) amount of distinct API calls to get needed information about a resource. George Reese has defined chatty API as any API that requires consumer to do more than a single call to perform a single, common operation. In mny opinion this is a bad thing because it is making the user do more work than they need to do in order to get information.
- What status code does a successful GET request return? The 200 OK status code means that the request was successful, but the meaning of success depends on the request method used: GET: The requested resource has been fetched and transmitted to the message body.
- What status code does an unsuccessful GET request return? 500: “There was an error on the server and the request could not be completed.” This is generic code that simply means “internal server error”. Something went wrong on the server and the requested resource was not delivered.
- What status code does a successful POST request return? The POST method is used to send data to the server. Perhaps the most common status code returned is 200.
- What status code does a successful DELETE request return? DELETE: This method SHOULD return status code 204 as there is no need to return any content in most cases as the request is to delete a resource and it was successfully deleted.


## Additional Information
