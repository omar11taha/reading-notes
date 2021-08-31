<!-- from online -->
# Lists and Keys

Sometimes this results in clearer code, but this style can also be abused. Like in JavaScript, it is up to you to decide whether it is worth extracting a variable for readability. Keep in mind that if the map() body is too nested, it might be a good time to extract a component.
Looping through and showing data from an array is an essential skill.
React uses the key prop create a relationship between the component and the DOM element. The library uses this relationship to determine whether or not the component should be re-rendered.

It is not recommended to use the index of the array as the key prop if you know the array will not be static. If the key is an index, reordering an item in the array changes it. Then React will get confused and re-render the incorrect element.
keys() is a built-in JavaScript method that returns an array of the given object's property names in the same order as we get with a standard loop. The Object. keys() method takes an object as an argument and returns the array of strings representing all the enumerable properties of a given object.

# How to Use the Spread Operator (…) in JavaScript
The spread operator is a new addition to the set of operators in JavaScript ES6. It takes in an iterable (e.g an array) and expands it into individual elements. The spread operator is commonly used to make shallow copies of JS objects. Using this operator makes the code concise and enhances its readability.

spread operator is useful for many different routine tasks in JavaScript, including the following:
* Copying an array.
* Concatenating or combining arrays.
* Using Math functions.
* Using an array as arguments.
* Adding an item to a list.
* Adding to state in React.
* Combining objects.
* Converting NodeList to an array.

“merge two arrays using spread operator”.

Spread syntax (...) allows an iterable such as an array expression or string to be expanded in places where zero or more arguments (for function calls) or elements (for array literals) are expected, or an object expression to be expanded in places where zero or more key-value pairs (for object literals) are expected.

Merge objects using the spread operator (...)
ES6 introduced the spread operator (...) which can be used to merge two or more objects and create a new one that has properties of the merged objects.

# How to Pass Functions Between Components

Components are an integral part of React. Each React application consists of several components, and each component may require user interaction that triggers various actions.
To achieve user interactivity, we can call functions and methods to accomplish specific operations in React. We pass data from parent to child or child to parent components using these actions.

Increment() Function
It takes a variable and increments (changes) its value, and also returns this value. The increment can be a positive or negative number. ... The Increment() function changes the value of its first argument.

Pass data or events from a parent component to a child component in both functional and class components.
import React from "react";export default function Child({data, onChildClick}) { return ( <div className="child"> ...
import Child from './Child'
import React from "react"; import "./styles.css";

export default function Parent() {
const myref=useRef();
​
const handleOnClick = () => {
if(myref. current) {
myref. current. sayHi();
}
}

