# Class 6 notes - Problem Domain, Objects, and the DOM

## JS Objects

1. **How would you describe an object to a non-technical friend you grew up with?**
An object is like a filling cabinet. The filing cabinet has files (variables or functions) and those files contain information.

2. **What are some advantages to creating object literals?**
Easier to work with than an array. Useful when you want to transfer a series of structured, related data.

3. **How do objects differ from arrays?**
You can store key value pairs all together.

4. **Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.**
When the property name has spaces or is a number.

5. **Evaluate the code below. What does the term `this` refer to and what is the advantage to using `this`?**
`this` refers to the object dog. This allows you to pull the given information while within the object.

>const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}

## DOM

1. **What is the DOM?**
Document Object Model. It is a programming interface for web documents.

2. **Briefly describe the relationship between the DOM and JavaScript**
<!-- From the MDN Docs -->
"The DOM is not a programming language, but without it, the JavaScript language wouldn't have any model or notion of web pages, HTML documents, SVG documents, and their component parts. The document as a whole, the head, tables within the document, table headers, text within the table cells, and all other elements in a document are parts of the document object model for that document. They can all be accessed and manipulated using the DOM and a scripting language like JavaScript."


