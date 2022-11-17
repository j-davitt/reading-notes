# Class 7 notes - Programming with JavaScript

**Control flow** is the order in which a computer executes statements in a script.

## Functions

**Functions** are a block of code designed to perform a particular task. a function is defined by `function` **name()**

>Example: `function name(parameter1, parameter2) {
    // code
}`

**Parameters** are listed inside parens(). Inside the function, the parameters behave as local variables and can only be accessed within the function.

When JavaScript reaches a `return` statement, the function will stop executing. Often a value is returned.

## Operators

The **Assignment Operator** (`=`) assigns value to a variable.

>Example: `let x = 5`

The **Adding Operator** (`+`) adds numbers. The **Multiplication Operator** (`*`) multiplies numbers.

### Arithmetic Operators

Used to perform arithmetic on numbers.

- `+` Addition
- `-` Subtraction
- `*` Multiplication
- `**` Exponentiation
- `/` Division
- `%` Modulus (Division Remainder)
- `++` Increment
- `--` Decrement

### Assignmnet Operators

Used to add value to a variable.

- `x = y` x = y
- `x += y` x = x + y
- `x -= y` x = x - y
- `x *= y` x = x * y
- `x /= y` x = x / y
- `x %= y` x = x % y
- `x **= y` x = x ** y

The `+` and `+=` operators can also be used to concatenate strings.

>'John' `+` ' ' `+` 'Doe' will result in 'John Doe'

>'What a nice ' `+=` 'day'  will result in 'What a nice day'

Adding two numbers will return a number but adding a number and a string will return a string.

### Comparison Operators

- `==` equal to
- `===` equal value and equal type
- `!=` not equal
- `!==` not equal value or not equal type
- `>` greater than
- `<` less than
- `>=` greater than or equal to
- `<=` less than or equal to
- `?` ternary operator

### Logical Operators

- `&&` logical and
- `||` logical or
- `!` logical not

### Type Operators

- `typeof` returns the type of variable
- `instanceof` returns true if an object is an instance of an object type