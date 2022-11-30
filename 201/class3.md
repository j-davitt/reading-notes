# Class 3 notes - HTML lists, Control Flow with JS, and the CSS Box Model

## HTML Lists

1. **When should you use an unordered list in your HTML document?**
When grouping a collection of items that do not have a numerical ordering, and their order in the list is meaningless.

2. **How do you change the bullet style of unordered list items?**
By using the CSS `list-style-type` property.

3. **When should you use an ordered list vs an unorder list in your HTML document?**
Use an ordered list when the order is meaningful example: directions, steps in a recipe, etc.

4. **Describe two ways you can change the numbers on list items provided by an ordered list?**
By using the CSS `list-style-type` or adding the `type` attribute.

## CSS Box Model

1. **Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?**
Margin is an invisible space around your box. It pushes other elements away from the box. Setting a negative margin can cause it to overlap  other things on a page.
Padding sits between the border and the content area and is used to push content away from the border. Any background applied to an element will display behind the padding.

2. **List and describe the four parts of an HTML elements box as referred to by the box model.**

- Content box: Area where your content is displayed. `inline-size block-size width height`

- Padding box: Sits around the content as white space. `padding`

- Border box: Wraps the content and any padding. `border` 

- Margin box: Outermost layer, wrapping content, padding, and border as whitespace between this box and other elements. `margin`

## JS Control Flow

1. **What `data types` can you store inside of an `Array`?**
Strings, numbers, objects, and even other arrays.

2. **Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?**

> `const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];`

Yes this is a valid array. It can be accessed by using `people[index]` or `people[index][index]`

3. **List five shorthand operators for assignment in javascript and describe what they do.**
- `=` Assignment: `x=f()`

- `+=` Addition: `x=x+f()`

- `-=` Subtraction: `x=x-f()`

- `*=` Multiplication: `x=x*f()`

- `/=` Division: `x=x/f()`

4. **Read the code below and evaluate the last expression and explain what the result would be and why.**

>  let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;

Since false == 0, it would be 10 + 0 and then concat dog. 10dog.

5. **Describe a real world example of when a conditional statement should be used in a JavaScript program.**
Anytime you would use an `if else` to set a condition to do one thing if true and another if false.

6. **Give an example of when a Loop is useful in JavaScript.**
loops are great for doing the same thing over and over. Example: Adding up all the values within an array.
