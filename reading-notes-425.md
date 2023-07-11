# Reading Notes Class 39 

- What concerns are addressed by Redux Toolkit?
    - Redux Toolkit was originally created to help address three common concerns about Redux:
        - "Configuring a Redux store is too complicated"
        - "I have to add a lot of packages to get Redux to do anything useful"
        - "Redux requires too much boilerplate code"
- What does configureStore() do? configureStore will automatically create the root reducer by passing this object to the Redux combineReducers utility
- How would I use createSlice()? The createSlice() function is used to simplify and reduce the code needed when creating application slices. It takes an object of options as an argument. The options are: name : the slice name used as the prefix of the generated action.

- What is Mobx? MobX is a battle-tested library that makes state management simple and scalable by transparently applying functional reactive programming.
- How does MobX make it “impossible” to produce an inconsistent state? MobX makes state management simple again by addressing the root issue: it makes it impossible to produce an inconsistent state. The strategy to achieve that is simple: Make sure that everything that can be derived from the application state, will be derived. Automatically.
- How would we build a reactive user interface? A human-to-computer user interface is said to be "reactive" if it has the following characteristics: The user is immediately aware of the effect of each "gesture". Gestures can be keystrokes, mouse clicks, menu selections, or more esoteric inputs. The user is always aware of the state of his/her data.

## Additional Information
