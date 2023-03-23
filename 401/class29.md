# Class 29 notes - Advanced State with Reducers

## Extracting State Logic into a Reducer

**What is the motivation for adding a reducer?**
You can compile all of your state logic outside your component in a single function.

**What are actions in the context of a reducer? How are they different than setting state directly?**
Instead of telling React “what to do” by setting state, you specify “what the user just did” by dispatching “actions” from your event handlers. (The state update logic will live elsewhere!) So instead of “setting tasks” via an event handler, you’re dispatching an “added/changed/deleted a task” action. This is more descriptive of the user’s intent.

**What common list operation is useReduce named for, and why?**
The function you pass to reduce is known as a “reducer”. It takes the result so far and the current item, then it returns the next result. React reducers are an example of the same idea: they take the state so far and the action, and return the next state. In this way, they accumulate actions over time into state.

**When should you switch from useState to useReducer?**
Use a reducer if you often encounter bugs due to incorrect state updates in some component, and want to introduce more structure to its code.
