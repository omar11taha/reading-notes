<!-- from online -->
## Understanding the JavaScript Call Stack

1. What is a ‘call’?
The call() method is a predefined JavaScript method. It can be used to invoke (call) a method with an owner object as an argument (parameter). With call() , an object can use a method belonging to another object.

2. How many ‘calls’ can happen at once?
The call() allows for a function/method belonging to one object to be assigned and called for a different object.
call() provides a new value of this to the function/method. With call(), you can write a method once and then inherit it in another object, without having to rewrite the method for the new object.

3. What does LIFO mean?
LIFO (Last-In-First-Out)

4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
![example](https://cs.gmu.edu/~kauffman/cs222/figs/side-by-side.png)

5. What causes a Stack Overflow?
The most-common cause of stack overflow is excessively deep or infinite recursion, in which a function calls itself so many times that the space needed to store the variables and information associated with each call is more than can fit on the stack

## JavaScript error messages

1. What is a ‘refrence error’?
In JavaScript, a reference error is thrown when a code attempts to reference a non-existing variable.

2. What is a ‘syntax error’?
An exception caused by the incorrect use of a pre-defined syntax. Syntax errors are detected while compiling or parsing source code. For example, if you leave off a closing brace ( } ) when defining a JavaScript function, you trigger a syntax error.

3. What is a ‘range error’?
A RangeError is thrown when trying to pass a value as an argument to a function that does not allow a range that includes the value. This can be encountered when: passing a value that is not one of the allowed string values to String.

4. What is a ‘tyep error’?
The TypeError object represents an error when an operation could not be performed, typically (but not exclusively) when a value is not of the expected type. A TypeError may be thrown when: an operand or argument passed to a function is incompatible with the type expected by that operator or function.

5. What is a breakpoint?
Setting Breakpoints
At each breakpoint, JavaScript will stop executing, and let you examine JavaScript values. After examining values, you can resume the execution of code (typically with a play button).

6. What does the word ‘debugger’ do in your code?
The debugger keyword stops the execution of JavaScript, and calls (if available) the debugging function. This has the same function as setting a breakpoint in the debugger. ... With the debugger turned on, this code will stop executing before it executes the third line.
