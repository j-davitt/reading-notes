# Class 27 notes - useState() Hook

## Thinking in React

**Summarize the five steps of thinking in react.**

Step 1: Break the UI into a component hierarchy

- draw boxes around the components in a mockup

Step 2: Build a static version in React

- Build a model without any interactivity. No state values yet.

Step 3: Find the minimal but complete representation of UI state

- Find absolute minimal representation of the state your app needs.

Step 4: Identify where your state should live

- Which component is responsible for the state.

Step 5: Add inverse data flow 

- allow for user input.

## State: A Component’s Memory

**What is one reason a local variable isn’t sufficient for managing a React component?**

Local variables don’t persist between renders. When React renders this component a second time, it renders it from scratch—it doesn’t consider any changes to the local variables.

**What is the argument to the useState hook, and what are the two parts of its return array?**

The only argument to useState is the initial value of your state variable. it returns the state variable with the value you stored and the state setter function.

**How can Component A access state from Component B?**

Remove state from the child components and add it to the closest shared parent component.
