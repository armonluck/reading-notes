# Class 8 Notes - *Operators and Loops*

## Expressions and Operators

An expression is a valid unit of code that resolves to a value. All complex expressions are joined by *operators*. There are two (2) types of expressions: those with side effects (like assigning values) and those that only *evaluate*.

1. Expression: `x = 7`
    - Expression uses the `=` operator to assign a value of `7` to the variable `x`.
2. Expression: `3 + 4`
    - Expression ONLY evaluates this addition problem. It is NOT part of a bigger construct, there is no variable declaration, and results will be immediately discarded.
    - Usually a programmer **mistake** because the evaluation does NOT produce any effects.

The *precedence* of operators determines the order that they are applied when evaluation ane expression. Arithmetic operators seem to follow normal order of operations learned in introductory math classes. For a complete table of operator precedence and exceptions to the rules please refer to the [Operator Precedence](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Operator_Precedence#table) page.

### Assignment Operators

### Comparison Operators

## Loops

Computerized version of the game where someone is told to take 'x' steps in one direction, then 'y' steps in another direction.

Loops are really helpful when you are trying to do something repeatedly. 

### *While* Loops

Used when we don’t know how long something will take or how many loops we want. 

> Structure: WHILE

`while (condition to evaluate is true){execute this code}`

`console.log(!false);` = not false = true
`console.log(!true);` = not true = false

> Loop will continue until input is "yellow"

`let response = prompt("What is my favorite color?");
while (response !== 'yellow'){response = prompt("Wrong, guess again");
}`

`console.log("Congrats, you guessed it!");`

> Example of self limiting loop

`let x = 0;
while(x < 100){
    console.log(x);
    x++;}`

### *For* Loops

> Structure: FOR

`for(initial value; condition to evaluate; increment){code to execute}`

> Example 1

`for (let i = 0; i < 3; i++){
    console.log(i);
    }`

// i = 0 | 0<5? T | console.log 0 | i is 1
// i = 1 | 1<5? T | console.log 1 | i is 2
// i = 2 | 2<3? T | console.log 2 | i is 3
// i = 3 | 3<3? F | BREAK LOOP

`function rateMyPage(){
    let rating = prompt("How many starts would you rate my page?");
    for (let i = 0; i < rating; i++){
        document.write("STAR");}`