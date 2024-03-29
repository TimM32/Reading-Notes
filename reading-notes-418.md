# Reading Notes Class 31

- Summarize the five principles for structuring state.
  A. Group related state. If you always update two or more state variables at the same time, consider merging them into a single state variable.
  B. Avoid contradictions in state. When the state is structured in a way that several pieces of state may contradict and “disagree” with each other, you leave room for mistakes. Try to avoid this.
  C. Avoid redundant state. If you can calculate some information from the component’s props or its existing state variables during rendering, you should not put that information into that         
  component’s state.
  D. Avoid duplication in state. When the same data is duplicated between multiple state variables, or within nested objects, it is difficult to keep them in sync. Reduce duplication when you can.
  E. Avoid deeply nested state. Deeply hierarchical state is not very convenient to update. When possible, prefer to structure state in a flat way.
  
- What problem do Contexts aim to solve?
  A. Create a context. (You can call it LevelContext, since it’s for the heading level.)
  B. Use that context from the component that needs the data. (Heading will use LevelContext.)
  C. Provide that context from the component that specifies the data. (Section will provide LevelContext.)
- What is one technique to try before useContext?
    A. Start by passing props. If your components are not trivial, it’s not unusual to pass a dozen props down through a dozen components. It may feel like a slog, but it makes it very clear which components use which data! The person maintaining your code will be glad you’ve made the data flow explicit with props.
    B. Extract components and pass JSX as children to them. If you pass some data through many layers of intermediate components that don’t use that data (and only pass it further down), this often means that you forgot to extract some components along the way. For example, maybe you pass data props like posts to visual components that don’t use them directly, like <Layout posts={posts} />. Instead, make Layout take children as a prop, and render <Layout><Posts posts={posts} /></Layout>. This reduces the number of layers between the component specifying the data and the one that needs it.
- What hook complements useContext for complex applications? useState and useReducer are two hooks that work well with useContext.

## Additional Information
