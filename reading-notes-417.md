# Reading Notes Class 29

- What is the motivation for adding a reducer? Reducers, as the name suggests, take in two things: previous state and an action. Then they reduce it (read it return) to one entity: the new updated instance of state. So reducers are basically pure JS functions which take in the previous state and an action and return the newly updated state.
- What are actions in the context of a reducer? How are they different than setting state directly? If you are not familiar with Redux, in short, a reducer is a pure function that takes previous state and action as an argument, and returns the next state. Actions are a piece of information that describes what happened, and based on that information, the reducer specifies how the state should change.
- What common list operation is useReduce named for, and why? The useReducer Hook is similar to the useState Hook. It allows for custom state logic. If you find yourself keeping track of multiple pieces of state that rely on complex logic, useReducer may be useful.
- When should you switch from useState to useReducer? useReducer is usually preferable to useState when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one. useReducer also lets you optimize performance for components that trigger deep updates because you can pass dispatch down instead of callbacks.

## Additional Information
