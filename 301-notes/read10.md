# In Memory Storage

## JavaScript Call Stack

1. What is a call stack?

- A call stack is a data structure that manages and keeps track of how functions in a program get executed.

2. How many ‘calls’ can happen at once?

- A call stack is single, so calls are done *one at a time*.

3. What does LIFO mean?

- *L*ast *I*n, *F*irst *O*ut. This means that the last function that is put on the stack is the first one to execute when the function gets called. 

4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.


5. What causes a Stack Overflow?

- If a function calls itself without having an exit point, this can create a **stack overflow**. It happens because there's not enough memory in the stack, and the function keeps executing with no end.

## JavaScript Error Messages

There are several types of error messages that happen in JavaScript. An **error** is a way for JavaScript to alert that something abnormal happened when the program was executed. Depending on the type of error, the program may stop executing at the point of the abnormality. Here are some of the errors that are often seen.

> 1. **Syntax Error** - A mistake occures in the syntax (structural writing) of the code. You might be missing a closing parenthesis or a semicolon.

> 2. **Reference Error** - If you create a variable or a function that is not defined, the program will try and *reference* to that variable and will throw a **reference error**. You *must* define all variables and functions for them to be usable. 

> 3. **Range Error** - When working with values, if you call something that goes beyond the expected range, you'll see a *range error*. An example would be if your array was 5 [0,1,2,3,4,5] and you called for (7). That exceeds the array length.

> 4. **Type Error**
If there is an attempt to execute an operation that is on a value of inappropriate type (example: trying to add a number with a string without parsing it), a *type error* will be thrown. 

When programming, you can add markers that will pause the execution of the script wherever a marker exists. This allows you to step through the code - essentially walking step by step through each execution - to identify if and where an error might take place. A type of breakpoint is a ***debugger*** statement, which lets you add a breakpoint tool directly into your written code. This is written out as *debugger*, and when you start your programming, it will pause when it hits this statement.  


## Things I Want to Know More About