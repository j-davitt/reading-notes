# Class 37 notes - Redux - Combined Reducers

## Multiple Reducers Example

**Why create multiple reducers?**


**How would you combine multiple reducers?**


**How will you manage state as an immutable object? why?**


## Redux Docs: Using Combined Reducers

**combineReducers is a utility function to simplify the most common use case when writing ___ _____ .**
Redux reducers

**Explain how combineReducers assembles the new state tree.**
combineReducers takes an object of the reducers as an argument. This returns a reducer function which is used to update state.

**How would you define initial state in an app using combineReducers?**
initial state is defined in the reducers.

## Redux Docs: Combined Reducer Syntax

**Why will you want to split your reducing functions as your app becomes more complex?**
splitting your reducing functions allows you to manage state as an immutable object.

**The _____ helper function turns an object whose values are different reducing functions into a single reducing function you can pass to____**
the combineReducers helper function turns an object whose values are different reducing functions into a single reducing function you can pass to createStore

**What is a popular convention when naming reducers?**
when naming reducers, use the name of the state slice they manage as the name of the reducer.
