# Class 8 notes - Operators and Loops

## Assignment Operators

An assignment operator assigns a value to its left operand based on the value of its right operand.

- `x+=f()` x = x + f()
- `x-=f()` x = x - f()
- `x*=f()` x = x * f()
- `x/=f()` x = x / f()
- `x%=f()` x = x % f()
- `x**=f()` x = x ** f()
- `x<<=f()` x = x << f() Left shift
- `x>>=f()` x = x >> f() Right shift
- `x>>>=f()` x = x >>> f() Unsigned right shift
- `x &= f()` x = x & f() Bitwise AND
- `x ^= f()` x = x ^ f() Bitwise XOR
- `x |= f()` x = x | f() Bitwise OR
- `x &&= f()` x && (x = f()) Logical AND
- `x ||= f()` x || (x = f()) Logical OR
- `x ??= f()` x ?? (x = f()) Nullish coalescing

If an expression evaluates to an object, then the left-hand side of an assignment expression may make assignments to properties of that expression.

>const obj = {};  
obj.x = 3;  
console.log(obj.x); //Prints 3  
console.log(obj); //Prints {x = 3}  
const key = 'y';  
obj[key] = 5;  
console.log(obj[key]); //Prints 5  
console.log(obj); //Prints {x: 3, y: 5}

### Destructuring

Syntax that makes it possible to extract data from arrays or objects using syntax similar to the construction of arrays and objects.

>const foo = ['one', 'two', 'three'];  
//Without destructuring  
const one = foo[0];  
const two = foo[1];  
const three = foo[2];  
//With destructuring  
const [one, two, three] = foo;

## Comparison Operators

Compares its operands and returns a logical value based on whether the comparison is true.

- Equal `==` 
- Not equal `!=`
- Strict equal `===`
- Strict not equal `!==`
- Greater than `>`
- Greater than or equal `>=`
- Less than `<`
- Less than or equal `<=`

## Loops

Loops offer a quick and easy way to do something repeatedly.

A `for` loop repeats until a specified condition evaluates to false.

>`for`([initialExpression]; [conditionExpression]; [incrementExpression])  
statement

1. `initialExpression`, if any, is executed. This usually initializes one or more loop counters.
2. `conditionExpression` is evaluated. if the value of `conditionExpression` is true, the loop statements execute. Otherwise, the `for` loop terminates.
3. The `statement` executes.
4. if present, the update expression `incrementExpression` is executed.
5. Control returns to step 2.

A `while` statement executes its statements as long as a specified condition evaluates to `true`.

>`while` (condition)  
statement

If the `condition` becomes `false`, the `statement` within the loop stops executing.

The condition test occure before `statement` in the loop is executed. If the condition returns `true`, `statement` is executed and `condition` is tested again. If the `condition` returns `false`, execution stops and the control is passed to the statement following `while`.