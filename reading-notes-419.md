# Reading Notes Class 32

- How do useReducer and useContext work together to simplify state management in a React application?

  Instead of passing the props down through each component, React Context allows you to broadcast props to the components below. The useReducer hook is used for complex state manipulations and state transitions. … useReducer is a React hook function that accepts a reducer function, and an initial state. The useContext hook is the React hook equivalent of the Context. Consumer of the Context API. It takes a React context object as the argument and returns the current value from the context. useReducer is an alternative version of useState for more complex state changes.

useReducer - The useReducer Hook is similar to the useState Hook. It allows for custom state logic. If you find yourself keeping track of multiple pieces of state that rely on complex logic, useReducer may be useful.
useContext - Context provides a way to pass data or state through the component tree without having to pass props down manually through each nested component.

Using these two hooks together helps to simplify state management by centralizing and organizing the state logic. This makes it easier for us to understand the information and it cuts down on the amount of coupling.
