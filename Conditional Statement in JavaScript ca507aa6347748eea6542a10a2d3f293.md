# Conditional Statement in JavaScript

Conditional Statements are used to perform different actions based on different conditions.

Conditional Statements 

Very often when you write code,  you want to perform different actions for different decisions.

You can use conditional statements in your code to do this:

In JavaScript we have the following conditional statements:

Use if to specify a block of code to be executed, if a  specified condition is true

Use else to specify a block of code executed, if the same condition is false

Use switch to specify many alternative blocks of code to be executed

The   switch statement is described in the    next chapter.

The if  statement syntax

if(condition)  

code to be executed }

Example:

```
if (num > 0) {
  console.log(`${num} is a positive number`)
}
//  3 i
```

if (condition) 

// block of code to be  executed }

else // block of code  to be executed if the condition is false }

Example:

```
let num = 3
if (num > 0) {
  console.log(`${num} is a positive number`)
} else {
  console.log(`${num} is a negative number`)
}
//  3 is a positive number
```