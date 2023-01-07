# Reading

## Understanding the JavaScript Call Stack

1. What is a ‘call’?

The call stack maintains a record of the position of each stack frame. It knows the next function to be executed (and will remove it after execution). This is what makes code execution in JavaScript synchronous.

2. How many ‘calls’ can happen at once?

It is single-threaded. Meaning it can only do one thing at a time.

3. What does LIFO mean?

Last In, First Out, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.

4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.



5. What causes a Stack Overflow?

A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

## JavaScript error messages

1. What is a ‘reference error’?

When you try to use a variable that is not yet declared.

2. What is a ‘syntax error’?

This occurs when you have something that cannot be parsed in terms of syntax.

3. What is a ‘range error’?

Manipulate an object with some kind of length and give it an invalid length will result in a range error.

4. What is a ‘type error’?

When the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

5. What is a breakpoint?

 A breakpoint is a point in the program where the code will stop executing.

6. What does the word ‘debugger’ do in your code?

The breakpoint can also be achieved by putting a debugger statement in your code in the line you want to break.

## Things I want to know more about

What is a good way to avoid getting a stack overflow?
