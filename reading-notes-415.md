# Reading Notes Class 27

- Summarize the five steps of thinking in react.

  A. Break the UI into a component hierarchy
      - Programming
      - CSS
      - Design
  B. Build a static version in React
  C. Find the minimal but complete representation of UI state
      - Does it remain unchanged over time? If so, it isn’t state.
      - Is it passed in from a parent via props? If so, it isn’t state.
      - Can you compute it based on existing state or props in your component? If so, it definitely isn’t state!
  D. Identify where your state should live
      - Identify every component that renders something based on that state.
      - Find their closest common parent component—a component above them all in the hierarchy.
      - Decide where the state should live:
      - Often, you can put the state directly into their common parent.
      - You can also put the state into some component above their common parent.
      - If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common parent component.
  E. Add inverse data flow

- What is one reason a local variable isn’t sufficient for managing a React component? Some local variables have limited scope, which means you may have trouble fully encorporating react into your project.
- What is the argument to the useState hook, and what are the two parts of its return array? useState is React Hook that allows you to add state to a functional component. It returns an array with two values: the current state and a function to update it. The Hook takes an initial state value as an argument and returns an updated state value whenever the setter function is called.
- How can Component A access state from Component B? If two components need access to the same state they should have a common ancestor where the state is kept. So component A is the parent of B and C. Component A has the state, and passes it down as props to B and C. If you want to change the state from B you pass down a callback function as a prop.

## Additional Information
