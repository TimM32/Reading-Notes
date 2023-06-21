# Reading Notes Class 28

- What is the main intended use case for the useEffect hook? The useEffect Hook allows you to perform side effects in your components. Some examples of side effects are: fetching data, directly updating the DOM, and timers. useEffect accepts two arguments. The second argument is optional.
- How does the effect’s logic interact with the component? 
A. When the component is first shown on the screen:
    - The effect’s code runs after the component is displayed.
    - You can use this to set things up, like initializing variables or fetching data.
B. Whenever the component’s data or appearance changes:
    - The effect’s code runs again.
    - You can respond to these changes by performing additional actions or updating the component’s state.
C. Before the component is removed from the screen:
    - The effect’s cleanup code (if provided) runs.
    - You can use this to clean up any resources or subscriptions created by the effect.
- What is the importance of the return value from the effect’s logic function? Why did we return a function from our effect? This is the optional cleanup mechanism for effects. Every effect may return a function that cleans up after it. This lets us keep the logic for adding and removing subscriptions close to each other.

## Additional Information
