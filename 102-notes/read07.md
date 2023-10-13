# Lesson 07 - Programming in JavaScript

When writing JavaScript, the computer will read the code in a specific order. This is called **control flow**, and it is what the computer uses to determine when it will execute statements within a script.

## Out of Order 

Let's say you want to make a peanut butter and jelly sandwich. The main steps are *get bread*, *spread peanut butter on one slice*, *spread jelly on a second slice*, *push the two pieces together*, *eat*.
However, it must be done in the correct order. You wouldn't want a person to do this, because it wouldn't be possible:

1. Eat
2. Push the two pieces together
3. Get bread
4. Spread the peanut butter on one slice
5. Spread the jelly on a second slice

This is the same for JavaScript; the order of execution is vital for success.

![Pb and j](https://cdn.tasteatlas.com/images/dishes/b63f3e8ef596416fa26a5ea073389e83.jpg?mw=900)
## JavaScript puts the **FUN** back in FUNCTION

When talking about JavaScript, a ***funtion*** is a chunk of code that is designed to do a task. To identifity a function, you must first write the word *function*. Next you are going to name what the function is, 
so that anytime you want to perform that task, you can ***invoke*** or call it to execute its task,  by the name you created. For this, we'll call the task mySandwich. 

function mySandwich(  )

The function paramaters lives withing the **parenthesis** ( ), and is necessary to call the function. In our example, let's have the compoments of a pb&j sandwich

function mySandwich ( topping1, topping2 )

let pb = topping1
let j = topping2

function mySandwich ( topping1, topping2 )
