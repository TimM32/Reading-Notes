# Reading Notes Class 312

- In your own words, describe what each group of status code represents:

- 100’s =
- 200’s =
- 300’s =
- 400’s =
- 500’s =

- What is a status code 202? Accepted 202
The request has been accepted for processing, but the processing has not been completed. The request may or may not eventually be acted upon, as it may be disallowed when processing actually takes place. there is no facility for status returns from asynchronous operations such as this.
- What is a status code 308? The HyperText Transfer Protocol (HTTP) 308 Permanent Redirect redirect status response code indicates that the resource requested has been definitively moved to the URL given by the Location headers.
- What code would you use if an update didn’t return data to a client? 204 No Content - A proper code for updates that don't return data to the client, for example when just saving a currently edited document.
- What code would you use if a resource used to exist but no longer does? 410 is used when the server knows there used to be a resource there, but there isn't anymore. 409 (“Conflict”) Sent when the client tries to perform an operation that would leave one or more resources in an inconsistent state.
- What is the ‘Forbidden’ status code? The HTTP 403 Forbidden response status code indicates that the server understands the request but refuses to authorize it.

- Why do we need to pull our MongoDB database string out of our server and put it into our .env? Applications use connection strings to identify the server instance and database to connect to and to determine what driver, login, etc. to use to connect to the SQL Server instance. Typically, the connection string will be stored in a configuration file somewhere within the application or web server.
- What is middleware? For example, a web server is middleware that connects websites to the backend database. When you submit a form on a website, your computer sends the request in XML or JSON to the web server.
- What does app.use(express.json()) do? This is a built-in middleware function in Express. It parses incoming requests with JSON payloads and is based on body-parser. Returns middleware that only parses JSON and only looks at requests where the Content-Type header matches the type option.
- What does the /:id mean in a route? from our list of routes, /posts/:id is the path that gets you to this function. The “:id” portion of that route specifies that whatever you put into that position will be passed as the id in the params map.
- What is the difference between PUT and PATCH? PUT is a technique of altering resources when the client transmits data that revamps the whole resource. PATCH is a technique for transforming the resources when the client transmits partial data that will be updated without changing the whole data.
- How do you make a default value in a schema? You can specify a default value for an item using the default keyword. When a data doesn't have a corresponding value, the value of this keyword will be used instead to do the validation checks. This keyword is not mandatory and the value of this keyword can be anything.
- What does a 500 error status code mean? 500 Internal Server Error
The HyperText Transfer Protocol (HTTP) 500 Internal Server Error server error response code indicates that the server encountered an unexpected condition that prevented it from fulfilling the request.
- What is the difference between a status 200 and a status 201? 200: “Everything is OK.” This is the code that is delivered when a web page or resource acts exactly the way it's expected to. 201: “Created.” The server has fulfilled the browser's request, and as a result, has created a new resource.


## Additional Information
