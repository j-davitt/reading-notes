# Class 3 notes - Passing Functions as Props

## React Docs

1. **What does .map() return?**
A new array based on the argument applied.

2. **If I want to loop through an array and display each value in JSX, how do I do that in React?**
Put it in curly brackets {}

3. **Each list item needs a unique ____.**
key

4. **What is the purpose of a key?**
keys help react identify which items have changed, are added, or are removed

## The Spread Operator

1. **What is the spread operator?**
Useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a functions arguments.

2. **List 4 things that the spread operator can do.**
copying an array, combining arrays, using math functions, using arrays as arguments.

3. **Give an example of using the spread operator to combine two arrays.**
`const hello = ['hello']`
`const world = ['world']`
`const helloWorld = [...hello,...world]`
`console.log(helloWorld) // 'helloworld'`

4. **Give an example of using the spread operator to add a new item to an array.**
`const first = [1,2,3]`
`const second = [4,5,...first]`
`console.log(second) // [4,5,1,2,3]`

5. **Give an example of using the spread operator to combine two objects into one.**
`const objOne = {hello: 'hi'}`
`const objTwo = {world: 'world'}`
`const objThree = {...objOne, ...objTwo, laugh: 'haha'}`
`console.log(objThree) // {hello: 'hi', world: 'world', laugh: 'haha'}`

## How to Pass Functions Between Components

1. **In the video, what is the first step that the developer does to pass functions between components?**
create it on the level of the information you are changing.

2. **In your own words, what does the increment function do?**
modify the value within an object

3. **How can you pass a method from a parent component into a child component?**
pass it down to the child component

4. **How does the child component invoke a method that was passed to it from a parent component?**
from props
