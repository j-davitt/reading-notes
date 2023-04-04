# Class 36 notes - Application State with Redux

## Dan Abramov Redux Tutorials

**What is the first principle of Redux?**
Everything that changes in an application, including data and UI state, is contained in a single object called the “state”.

**what is a store and what do we use our reducers for within that store?**
A store is an object that holds the application's state tree. We use reducers to update the store.

**Name three Redux store methods given to us by createStore and describe their use.**
- getState() - returns the current state of the store
- dispatch() - dispatches an action to the store
- subscribe() - subscribes a listener to the store

**Explain to a non-technical recruiter what combineReducers() does and why it is useful.**
combineReducers() is a function that takes an object as an argument. The return value is a reducer function. The reducer function is used to update the store.
