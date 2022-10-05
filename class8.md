# Class 8 Notes - *Operators and Loops*

## Expressions and Operators

An expression is a valid unit of code that resolves to a value. There are two (2) types of expressions

## Loops

Computerized version of the game where someone is told to take 'x' steps in one direction, then 'y' steps in another direction.

Loops are really helpful when you are trying to do something repeatedly. 

### While Loops

Used when we don’t know how long something will take or how many loops we want. 

> Structure: WHILE

`while (condition to evaluate is true){execute this code}`

`console.log(!false);` = not false = true
`console.log(!true);` = not true = false

> Loop will continue until input is "yellow"

`let response = prompt("What is my favorite color?");
while (response !== 'yellow'){response = prompt("Wrong, guess again");
}`

> Example of self limiting loop

`let x = 0;
while(x < 100){
    console.log(x);
    x++;}`
