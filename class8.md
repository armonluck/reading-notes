# Class 8 Notes - *Operators and Loops*

## Expressions and Operators

An expression is a valid unit of code that resolves to a value. There are two (2) types of expressions

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