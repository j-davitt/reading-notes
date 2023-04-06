# Class 39 notes - Redux: Additional Topics

## Redux Toolkit (RTK)

**What concerns are addressed by Redux Toolkit?**
- "Configuring a Redux store is too complicated"
- "I have to add a lot of packages to get Redux to do anything useful"
- "Redux requires too much boilerplate code"

**What does configureStore() do?**
 wraps createStore to provide simplified configuration options and good defaults. It can automatically combine your slice reducers, adds whatever Redux middleware you supply, includes redux-thunk by default, and enables use of the Redux DevTools Extension.

**How would I use createSlice()?**
accepts an object of reducer functions, a slice name, and an initial state value, and automatically generates a slice reducer with corresponding action creators and action types.

## MobX

**What is Mobx?**
mobx is a simple, scalable and battle tested state management solution. It makes state management simple by making it impossible to produce an inconsistent state.

**How does MobX make it “impossible” to produce an inconsistent state?**
By making sure that everything that can be derived from the application state, will be derived. Automatically.

**How would we build a reactive user interface?**
By using the observer function to wrap the component
