# Reading Notes Class 36

- What is the first principle of Redux? First, Single Source of Truth. This means that we should only store one state object on our application, no more, no less.
- What is a store and what do we use our reducers for within that store? The store has the current state value and reducer function inside of itself. getState returns the current state value. subscribe keeps an array of listener callbacks and returns a function to remove the new callback. dispatch calls the reducer, saves the state, and runs the listeners.
- Name three Redux store methods given to us by createStore and describe their use.
    - getState(): This method is used to retrieve the current state from the Redux store. It returns the current state object stored in the store. We can use getState() to access and read the data stored in the store from our application components or other parts of the code.
    - dispatch(action): The dispatch method is used to trigger an action in Redux, takes an action object as an argument and sends it to the store. 
    - subscribe(listener): The subscribe method allows us to register a listener function that will be called whenever the state in the store changes. It takes a listener function as an argument, which will be invoked every time an action is dispatched and the state is updated. 
- Explain to a non-technical recruiter what combineReducers() does and why it is useful. The combineReducers function allows you to combine multiple reducer functions into a single function that can be passed to the Redux store. The resulting reducer function handles multiple slices of the state, each controlled by a separate reducer function. Basically, you can multi-task with combineReducer(), cutting down on time and data space or energy to put in regards to a person.


## Additional Information
