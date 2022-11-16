# Class 6 notes - JavaScript

JavaScript is a lightweight programming language.

### Major Components

1. The language itself.
2. **The DOM API** - How the language interacts with various parts of a web page.
3. **The Server API**(or just API)

You can either **embed** the JavaScript directly in the HTML file, or **include** an external JavaScript file. Embedding will have the code wrapped in `<script></script>`.

## Syntax

Variables are containers for storing values. If you think the value of a variable will change, use `let` otherwise use `const`. All variables must be identified with unique names, called **identifiers**.

It is good practice to declare all variables at the beginning of a script.

If you put a number in quotes, the rest of the numbers will be treated as strings and concatenated.

>Example: `let x = "5" + 2 + 3` returns `523`.
<br> 
`let x = 2 + 3 + "5"` returns `55`.

