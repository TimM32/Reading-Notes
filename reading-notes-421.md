# Reading Notes Class 34

- Explain the different between a query string parameter and a path parameter. While query parameters describe how to look, path parameters show your program where to look. Path parameters are part of the endpoint URI and are required to have a value. Think of path parameters as the file system in your endpoint URL, guiding the request to the answer it seeks.
- What would our API URL with a path id parameter be given the following information:
    - Domain: http://our-site.com
    - v3
    - model name: stuff
    - id: things
- We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend. Think of APIs like legos, they are extremely customizable so that you can do whatever it is that you need that API to help with you. You can even build upon an API with another API. These APIs can be built so that they can continue to learn new things and be built in new and creative ways. This is extremely helpful because it allows devs to not feel like they are stuck in a box.

- Describe how you would use middleware to implement basic and bearer auth. Every route must be authenticated if the user is not authenticated then he is not able to call the above mentioned routes,so every GET,POST calls required authentication.In this case we build a authtication middleware.
- Describe the handshake necessary to implement OAuth. The OAuth 2.0 handshake involves the Authorization request and the access token request. The access token is the end goal because it allows the app to finally access the user's information.
- Describe how Role Based Access Control works to a non-technical friend. This is quite simple, think of it like a company. The ground level employee has ability to access only certain floors at the office, their mananger can access a couple more, the team lead can acces a a few more than the previous two and the CEO has full access to all floors and all projects that are going on.

# Additional Information
