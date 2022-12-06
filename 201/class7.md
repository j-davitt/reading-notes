# Class 7 notes - Object-Oriented Programming, HTML Tables

## Domian Modeling

**Explain why we need domain modeling.**
Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.

## HTML Table Basics

1. **Why should tables not be used for page layouts?**
Reduces accessability for visually impaired users. Produce lag. Not automatically responsive.

2. **List and describe 3 different semantic HTML elements used in an HTML `<table>`.**
`<td>` is a table cell, the smallest container inside a table.
`<tr>` is a table row, used to break up `<td>` into rows.
`<th>` is a table header.

## Introducing Constructors

1. **What is a constructor and what are some advantages to using it?**
A constructor is a function called when using the `new` keyword. It will create a new object, bind `this` to the new object so it can be used in your constructor code, run the code in the constructor, return the new object.

2. **How does the term `this` differ when used in an object literal versus when used in a constructor?**
When used in an object literal it is scoped to that object. When used in a constructor it is scoped to the new object being created.
