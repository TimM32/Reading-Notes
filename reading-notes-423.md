# Reading Notes Class 37

- Why create multiple reducers? Multiple slice reducers can respond to the same action, independently update their own slice as needed, and the updated slices are combined into the new state object. Because this pattern is so common, Redux provides the combineReducers utility to implement that behavior.
- How would you combine multiple reducers? In order to let us combine multiple reducers together, Redux provides the combineReducers() method.
- How will you manage state as an immutable object? why? The most simple solution is to use immutable objects. If the object needs to be updated, you have to create a new object with the new value since the original one is immutable and cannot be changed. You can use reference equality to know that it changed.

- combineReducers is a utility function to simplify the most common use case when writing ___ _____ . Redux Reducers
- Explain how combineReducers assembles the new state tree. In order to assemble the new state tree, combineReducers will call each slice reducer with its current slice of state and the current action, giving the slice reducer a chance to respond and update its slice of state if needed. So, in that sense, using combineReducers does "call all reducers", or at least all of the slice reducers it is wrapping.
- How would you define initial state in an app using combineReducers? There are two main ways to initialize state for your application. The createStore method can accept an optional preloadedState value as its second argument. Reducers can also specify an initial value by looking for an incoming state argument that is undefined , and returning the value they'd like to use as a default.

- Why will you want to split your reducing functions as your app becomes more complex? It will be much easier not only for yourself but someone else to work on your code and keep things in order if you split up the responsibilities of the functions the more complex the app becomes. You don't want one funciton being in charge of to much in case something were to go wrong with that function it might collapse your whole app.
- The _____ helper function turns an object whose values are different reducing functions into a single reducing function you can pass to ____. combineReducers, createStore
- What is a popular convention when naming reducers? combineReducers({ counter, todos })

## Additional Information
