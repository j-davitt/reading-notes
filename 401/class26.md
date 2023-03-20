# Class 26 notes - Component Based UI

## Your First Component

**What are the building blocks of a React app?**
Components

**What is the difference between an element and a React component?**
A component is a combination of markup, CSS, and javascript into a reusable UI element 

**What are some advantages of React’s component based architecture?**
They can be nested and organized. Each component is modularized.

## introducing JSX

**What is JSX and why do we use it?**
a syntax extension to JavaScript. Used to describe what the UI should look like.

**Describe the process of embedding JavaScript expressions in JSX.**
Just wrap it in curly brackets.

**Is it safe to embed user input in JSX? Explain.**
yes, be default React DOM escapes any value embedded in JSX before rendering them.

## rendering elements

**Explain what a React Component is to a non-technical friend.**


**Describe mutability and React Components, specifically, how is the UI updated?**
React elements are immutable. Once you create an element, you can’t change its children or attributes.

**If changes are made to the UI, what does React update?**
React DOM compares the element and its children to the previous one, and only applies the DOM updates necessary to bring the DOM to the desired state.
