# Class 10 notes - In Memory Storage

## Understanding the JavaScript Call Stack

- **What is a ‘call’?**
function invocation

- **How many ‘calls’ can happen at once?**
one

- **What does LIFO mean?**
last in, first out

- **What causes a Stack Overflow?**
A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

## JavaScript error messages

- **What is a ‘reference error’?**
When trying to use a variable that is not yet declared.

- **What is a ‘syntax error’?**
something that cannot be parsed in terms of syntax.

- **What is a ‘range error’?**
when manipulating an object with some kind of length and give it an invalid length.

- **What is a ‘type error’?**
when the type(number, string, etc) is incompatible

- **What is a breakpoint?**
it stops the code to see how it is running

- **What does the word ‘debugger’ do in your code?**
creates a breakpoint
