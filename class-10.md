# Error Handling and Debugging

Order of exectution:

To find the source of errors it helps to know how scripts are processed. The order in which statements can be complicated, but alot of them cannot complete until another statement of function can be run.

Exuctution Contexts

The JavaScript interpreter uses the concept of execution contexts.There is one global execution context.
You will be able to find the errors in your code easily if you understand execution centexts that have two stages and stacks.

Debugging is a way of saying the process of finding errors in your code and it involves the process of deduction.

You always want  to use the console to narrow down the area where the error is located so you can find the exact error.

JavaScript has 7 different types of errors and they create their own error object, which can tell you what line it is located on and will give you a description of the error.

If you know that you might get an error you can handle it right by using these statements:
 - try
 - catch
 - finally

you need to use them to give your users helpful feedback.

[<==Back](README.md)