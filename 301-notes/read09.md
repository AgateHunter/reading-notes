# Functional Programming

## Functional Programming Concepts

1. What is functional programming?

Functional programming is one style of programming where the user writes inputs (functions) that create outputs, without modifying the data that is outside of the function. Each function is designed to do just one thing, and do it well. You are creating without modifying; your function will always do the one thing it was created to do.  

2. What is a pure function and how do we know if something is a pure function?

- If a function gives the same result for the same input, it is a pure function. Nothing internal or hidden or external will impact the result.

- If a function doesn't cause any changes outside of itself - no modification to other data structures, or do anything to change things outside of itself - then it is a pure function.

3. What are the benefits of a pure function?

Pure functions make code easier to reason with and test.  You don't have to worry about the function itself changing its behavior, or causing change in other data.

4. What is immutability?

Data that ***cannot be changed*** after it is created. Once you create data that is immutable, you can't make any changes. You'll instead need to create a new object with the value you want.

5. What is *Referential transparency*?

A function that continually and consistently provides the same result for the same input. When you add *pure function* with *immutable data*, your result will be the concept of referential transparency.

## Node JS Tutorial

1. What is a node module?

A *module* in Node.Js is a piece of code that can be reused that aligns with a single file. Node modules are ways to break up the code into many pieces so they don't all live in one file. It makes for easier management and accessibility to extend and refractor.

2. What does the word 'require' do?

**Require** is a function in node.js that lets external modules (files) into whatever script you're working on. You can bring in third-party packages and modules.

3. How do we bring another module into the file that we are working in?

You'll need to do more than just 'require'; you must explicitly state what part of the module will be made available to other files.

4. What do we have to do to make a module available?.

You'll write *module.exports =* then state what function is to be set. Then you'll create a variable name = to the 'require' function

> **Example** var example = require('./example');

## Things I would like to know more about.

- Do you list out all the functions that can be used in one line of code, or do you create multiple statements for each function that will be used when a module is called? What is best practice?
