# Reading Notes Class 403

- Classes are a template for creating ____. a particular form of object.
- Can a class declaration be hoisted? Hoisting is a mechanism that inserts variable and function declaractions into memory ahead of assignment and initialization within the given scope of execution. const , let , function expressions and classes do not get hoisted, and cannot be read or accessed before their declaration.
- How would you describe a constructor and contextual “this” to a non-technical friend? "this" when being used in a constructor refers to the something being made, for if you were trying to refer to a person it you be them or they.

- Within Express, what does routing refer to? Routing refers to how an application's endpoints (URIs) respond to client requests. For an introduction to routing, see Basic routing. You define routing using methods of the Express app object that correspond to HTTP methods; for example, app.get() to handle GET requests and app.post to handle POST requests.
- What is the difference between a route path and a route method? <Route>: Route is the child component that renders a specific UI component when the URL matches the specified path. The path attribute specifies the path name we assign to the component and the element attribute refers to the component to render when the URL matches.
- When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter? you want to add next when you are trying to guide the code to go to the next operation, if you want to include next and create an error you fill that method in with anything, so it could look like next() when moving to the next function or nex('some writing') if you dont!

- What is an Express Router? Express Routers are a way to organize your Express application such that your primary app. js file does not become bloated and difficult to reason about. As you're building an Express application or API, you'll soon notice that the routes continue to pile up in app. js. This makes the file quite long and hard to read.
- By what mean do we initialize express.Router() in an express server? we use the fucntion app.use and then /(here is where we can put the name of the route to be more precise)
- What do we use route middleware for? Middleware provide a convenient mechanism for inspecting and filtering HTTP requests entering your application. For example, Laravel includes a middleware that verifies the user of your application is authenticated.


## Addictional Information
