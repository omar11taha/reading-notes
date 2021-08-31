## React Docs - Forms
In a controlled component, form data is handled by a React component. The alternative is uncontrolled components, where form data is handled by the DOM itself. To write an uncontrolled component, instead of writing an event handler for every state update, you can use a ref to get form values from the DOM.
The most basic way of working with forms in React is to use what are referred to as “uncontrolled” form inputs. What this means is that React doesn’t track the input’s state. HTML input elements naturally keep track of their own state as part of the DOM, and so when the form is submitted we have to read the values from the DOM elements themselves.
Event Handler Syntax and Notes
DOM level: a. Make sure that the DOM element has an event attribute that triggers your event handler function. b. ...
Script level: At the script level, simply define your handler function: function funcName() { const val = findHTMLelement.value

## The Conditional (Ternary) Operator Explained
A ternary operator allows you to assign one value to the variable if the condition is true, and another value if the condition is false. ... A ternary operator makes the assignment of a value to a variable easier to see, because it's contained on a single line instead of an if else block.

if (x % 2 == 0)
    System.out.println("Even");
else
    System.out.println("Odd");

