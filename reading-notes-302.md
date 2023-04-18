# Reading Notes Class 302


- Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’? The render happens first.
- What is the very first thing to happen in the lifecycle of React? The first cycle is the Mounting phase,
- Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
  Constructor then Render then React Updates then ComponentDidMount then ComponentWillUnmount
- What does componentDidMount do? componentDidMount. The componentDidMount() method is called after the component is rendered. This is where you run statements that requires that the component is already placed in the DOM.


- What types of things can you pass in the props? We can pass any data type as props in React components: object, array, boolean, number, string, function, etc. Yes, it is possible to pass objects to React components. Let's say you have the below object in a parent component and want to pass it to a child component so it can display the object's property values.
- What is the big difference between props and state? The key difference between props and state is that state is internal and controlled by the component itself while props are external and controlled by whatever renders the component.
- When do we re-render our application? Re-render happens when React needs to update the app with some new data. Usually, this happens as a result of a user interacting with the app or some external data coming through via an asynchronous request or some subscription model.
- What are some examples of things that we could store in state? You can store components, objects and other vaules inside of states witinreact.


## Additional Information
