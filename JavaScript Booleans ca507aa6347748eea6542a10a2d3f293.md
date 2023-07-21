# JavaScript Booleans

A JavaScript Boolean represents one or two values: true or false.

You can use the Boolean()function to find out if an expression(or a variable) is true.

Comparisons and Conditions

Operator Description Example

==           equal to      if(day==Monday)

>greater than              if(salary>9000)

<less than                    if(age<18)

The boolean value of 0 is false:

let x=0;

Boolean(x);

The Boolean value of -0 is false:

let x=-0;

Boolean(x);

The  Boolean value  of undefined is false:

let x;

Boolean(x);

The Boolean value of null is false:

let x=null;

Boolean(x);

The Boolean value of  false is false:

let x=false;

Boolean(x);

The Boolean value of NaN is false:

let x=10/hallo;

Boolean(x);

JavaScript Booleans as Objects 

Normally javaScript booleans are primitive values created from literals:

let x=false;

But Booleans can also be defined as objects with the keyword   new

let  y=new Boolean(false);

let x=false;

let y=new Boolean(false);

It is not advisable to create Boolean objects.

The new  keyword complicates the code and slows down the execution speed.

Boolean objects can produce  unexpected results:

When using the== operator,   x     and   y are       equal

let x=false;

let y=new Boolean(false);

When  using the === operator, x and y are not equal:

let x=false;

let y= new Boolean(false); 

    

### Assignment Operator

An equal sign in JavaScript is an assignment operator. It uses to assign a variable.

![Untitled](JavaScript%20Booleans%20ca507aa6347748eea6542a10a2d3f293/Untitled.png)

### Arithmetic Operators

Arithmetic operators are mathematical operators.

- Addition(+): a + b
- Subtraction(-): a - b
- Multiplication(*): a * b
- Division(/): a / b
- Modulus(%): a % b
- Exponential(**): a ** b

### Comparison Operators

In programming we compare values, we use comparison operators to compare two values. We check if a value is greater or less or equal to other value.

### Logical Operators

The following symbols are the common logical operators: &&(ampersand) , ||(pipe) and !(negation). The && operator gets true only if the two operands are true. The || operator gets true either of the operand is true. The ! operator negates true to false and false to true.

### Increment Operator

In JavaScript we use the increment operator to increase a value stored in a variable. The increment could be pre or post increment. Let us see each of them:

1. Pre-increment

```
let count = 0
console.log(++count)        // 1
console.log(count)          // 1
```

1. Post-increment

`let count = 0
console.log(count++)        // 0`

## Date Object

Time is an important thing. We like to know the time a certain activity or event. In JavaScript current time and date is created using JavaScript Date Object. The object we create using Date object provides many methods to work with date and time.The methods we use to get date and time information from a date object values are started with a word *get* because it provide the information. *getFullYear(), getMonth(), getDate(), getDay(), getHours(), getMinutes, getSeconds(), getMilliseconds(), getTime(), getDay()*

![https://github.com/Asabeneh/30-Days-Of-JavaScript/raw/master/images/date_time_object.png](https://github.com/Asabeneh/30-Days-Of-JavaScript/raw/master/images/date_time_object.png)

- 
- 
-