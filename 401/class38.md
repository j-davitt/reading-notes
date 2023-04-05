# Class 38 notes - Async Actions

## async actions

**Why use Redux middleware?**
Redux reducers must never have side effects. Middleware allows us to have side effects in our Redux app.

**Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.**
An event goes to the handler which then dispatches an action.The action hits the middleware which sends a request to an API and attaches information to the action. The action is then sent to the reducer which then updates the state. The state is then sent to the UI which then renders the new state.

**How are we accommodating async in our Redux app?**
Async actions are handled by middleware. We use redux-thunk to handle async actions.

## thunk middleware

**Why would you need redux-thunk middleware?**
Allows writing functions with logic inside that can interact with a redux store.

**Redux Thunk middleware allows you to write action creators that return a ____ instead of an action.**
Function

**Describe how any return value from the inner thunk function will be made available.**
as the return value of the dispatch method.
