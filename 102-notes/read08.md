# Reading 08 - Operators and Loops

**What Is an Operator? What's an Expression?**

*Operators* are symbols to assign the value to a variable. It informs the code of what is needs to do. Common operators are things that we are familiar with in subjects like math.
<br>
1. '**+**'       add 
2. ' **-** '     subtract 
3. ' **/** ' divide
4. ' * ' multiply

*Expressions* is code that produces some sort of **value**. We need to look at the expression to know what its value is. Here is a list of common expression in JavaScript:

+ 52 | Number
+ 'Hello To Everyone' | String
+ myLearning | Variable
+ 100 + 100 | Calculation
+ myLearning( ) | A Function that returns a value

## Loops

![Infinite Loop of Doom](https://assets-global.website-files.com/5dbb30f00775d4350591a4e5/633c5d3fcd492900c9467595_microverse%20infinite%20loops%20(1)%20(1).jpg)

A ***loop*** is a block of code that runs over and over, generating new values, until it reaches defined conditions to stop. It is a simple way to repeate code, without having to write it multiple times. There are few types of loops to focus on:

### For Loop

A *for loop* will complete its cycle once it has checked all the conditions have been met. Once the condition is no longer met, it will stop its loop.

#### Example

for (let i = 0; i <= 20; i++) 
{
  consoloe.log(i);
}

### While Loop

A *while loop* will run as long as a condition is true. If a condition is not true, it will not run. Therefore, a condition must be defined so that the loop can check against it. 

#### Example

while (i <=20) {
  console.log(i);
  i++;
}
