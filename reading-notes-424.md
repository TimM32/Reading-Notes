# Reading Notes Class 38

- Why use Redux middleware? Redux Middleware allows you to intercept every action sent to the reducer so you can make changes to the action or cancel the action.
- Consider the Redux Async Data Flow Diagram. Describe the flow in your own words. The middleware intercepts the action and then it is able to perform jobs suchs as API calls (among others). Once this aysne action is completes, it returns a success or failure and then the reducer updates the state based on whether it has succeed or failed.
- How are we accommodating async in our Redux app? Redux Thunk

- Why would you need redux-thunk middleware? Redux Thunk is a middleware that allows Redux to return functions rather than actions. This allows you to work with promises while delaying actions.
- Redux Thunk middleware allows you to write action creators that return a ____ instead of an action. a Fucntion
- Describe how any return value from the inner thunk function will be made available. It is made available with the Dispatch function

## Additional Information
