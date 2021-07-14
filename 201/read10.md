# JS 
## error handling and debugging
To find the source of an error, it helps to know how scripts are processed.
The order in which statements are executed can be complex.
Error objects can help you find where your mistakes are
and browsers have tools to help you read them
![Error](https://cdn.ourcodeworld.com/public-media/articles/donot-access-prototype-method-vuejs-1-5fe3f7f3ebf81.png)
* BREAKPOINTS
![](https://d3of8ou1mslcoj.cloudfront.net/content/uploads/2012/05/javascript_breakpoints1.png)
<!-- from the book  -->
* If you understand execution contexts (which have two
stages) and stacks, you are more likely to find the error
in your code.
* Debugging is the process of finding errors. It involves a
process of deduction.
* The console helps narrow down the area in which the
error is located, so you can try to find the exact error.
* JavaScript has 7 different types of errors. Each creates
its own error object, which can tell you its line number
and gives a description of the error.
* If you know that you may get an error, you can handle
it gracefully using the try, catch, finally statements.
Use them to give your users helpful feedback.
