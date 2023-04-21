# Reading Notes Class 304

- What is a ‘Controlled Component’? In React, a controlled component is a component that is controlled by React state, while an uncontrolled component is a component that maintains its own internal state. A controlled component receives its current value and an update callback via props, and the parent component manages the state of the component.
- Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why. We should do it as soon as they submit the form because we wont that data stored right away so that we can start having the rest of our app or website process the data for the next step. We can always go back and alter the data as it is coming in but if we ahve to wait for it then it might not do what we want it to do when we want it to do it !
- How do we target what the user is entering if we have an event handler on an input field?  Use the value Propert. You can simply use the value property of the DOM input element to get the value of text input field. The following example will display the entered text in the input field on button click using JavaScript.
- Why would we use a ternary operator? 
A ternary operator evaluates conditions to present a true or false value, but with more concise syntax and parameters than other methods. The condition is what your code will evaluate to decide the correct output. The exprIfTrue is the expression you will get if the condition is evaluated as true.

## Additional Information
