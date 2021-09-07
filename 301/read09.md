<!-- from online -->
## Functional Programming Concepts

1. What is functional programming?
Functional programming means using functions to the best effect for creating clean and maintainable software. This article illustrates the concepts behind the functional paradigm with practical examples in JavaScript and Java.

2. What is a pure function and how do we know if something is a pure function?
The definition of a pure function is: The function always returns the same result if the same arguments are passed in. It does not depend on any state, or data, change during a program's execution. It must only depend on its input arguments.

3. What are the benefits of a pure function?
One of the major benefits of using pure functions is they are immediately testable. They will always produce the same result if you pass in the same arguments. They also makes maintaining and refactoring code much easier.

4. What is immutability?
Immutable. js is a library that supports an immutable data structure. It means that once created data cannot be changed. It makes maintaining immutable data structures easier and more efficient. The tool supports data structure like: List, Map, Set and also structures that are not implemented in .

5. What is Referential transparency?
Referential Transparency emphasizes that an expression in a JavaScript program may be replaced by its value or any other variable having the same value without changing the result of the program. As a result, methods should always return the same value for the given argument without any side effects.

## Node JS Tutorial for Beginners #6 - Modules and require()

1. What is a module?
JS modules (also known as “ES modules” or “ECMAScript modules”) are a major new feature, or rather a collection of new features. You may have used a userland JavaScript module system in the past. ... All of these module systems have one thing in common: they allow you to import and export stuff.

2. What does the word ‘require’ do?
The require() method is used to load and cache JavaScript modules. So, if you want to load a local, relative JavaScript module into a Node. js application, you can simply use the require() method.

3. How do we bring another module into the file the we are working in? 
To include functions defined in another file in Node.js, we need to import the module. we will use the require keyword at the top of the file.

The result of require is then stored in a variable which is used to invoke the functions using the dot notation.

4. What do we have to do to make a module available?
The first thing you do to get access to module features is export them. This is done using the export statement. You can export functions, var , let , const , and — as we'll see later — classes. They need to be top-level items; you can't use export inside a function, for example.

