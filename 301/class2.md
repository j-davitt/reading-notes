# Class 2 notes - State and Props

1. **Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?**
render

2. **What is the very first thing to happen in the lifecycle of React?**
Mounting

3. **Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates**
constructor, render, react updates, componentDidMount, componentWillUnmount

4. **What does componentDidMount do?**
Dom manipulations and network requests.

## React state vs props

1. **What types of things can you pass in the props?**
title and subtitle and other things for a component

2. **What is the big difference between props and state?**
props are like arguments to a function/handled **OUTSIDE** of the component. state is handled **WITHIN** a component.

3. **When do we re-render our application?**
changing the state within an application

4. **What are some examples of things that we could store in state?**
counters or other things that will change within an application.
