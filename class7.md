# Class 7 Notes - *Programming with JavaScript*

## *Useful JS Commands*

command: `use strict`

- tells JavaScript to perform based on strict JS rules

command: `.toLowerCase()`

- converts users input to ONLY lowercase

command: `.toUpperCase()`

- converts users input to ONLY uppercase

## [Control Flow](https://developer.mozilla.org/en-US/docs/Glossary/Control_flow)

The ***control flow*** is the order in which a computer executes/runs statements in a script.

Code is typically executed/ran from the first line in a file down to the last line. Exceptions to this rule are infrequent but include structures that change the control flow such as *conditionals* and *loops*.

An example of this exception can occur when a user is entering data on a webpage form. If a user attempts to *submit* data, but has left a required field empty (usually denoted by an asterisk), then the script will stop and prompt the user to fill in the missing information. A **conditional** structure or `if...else` statement is used in this case so that different code is executed depening on whether necessary information has been completed or not.

> Example:
`if (isEmpty(field)) {
    promptUser();
} else {
    submitForm();
}`

A typical script in JavaScript or PHP (Hypertext Preprocessor) includes many control structures including conditionals, loops, and functions.

## [JavaScript Functions](https://www.w3schools.com/js/js_functions.asp)

A **function** is a block of code which performs/executes a specific task. A JS funcction is executed when it is **invoked** or called.

### Function Syntax

A JS function is defined with the `function` keyword followed by a name or unique identifier and then parentheses `()`. Similar to variable names, function names can contain letters, digits, underscores, and dollar signs. Parentheses can include multiple **parameters** separated by commas: `(parameter1, parameter2)`. The code that will be executed by the function is then placed inside curly brackets `{}`.

### Function Invocation

Code inside the function will execute when something **invokes** or "calls" the function. Functions are invoked when:

- An event occurs, e.g. a button click
- It is invoked (called) from the JavaScript code
- Automatically (self-invoked)

The () operator invokes the function in a set of code. For example, `myFunction` is the function object and `myFunction()` is the function result.

### Function Return

When JS receives a `return` statement, the function will stop executing. Functions usually compute a **return value** which is "returned" back to the "caller".

> Examples of Function Structure

`function uniqueName(parameters){code to be executed}`

`function addTwoNumbers(number1, number2){return number1 + number2}`

`console.log(number1 + number2);}`

`addTwoNumbers(5, 3);` OR `addTwoNumbers(“Hello “, “world”);`

### Why are Functions Used?

Functions allow for code to be re-used by defining it once and using it repeatedly throughout a script. The same code can also be used multiple times with different **arguments** to produce different results/outputs.

## [JavaScript Operators](https://www.w3schools.com/js/js_operators.asp)

**Types of JavaScript Operators:**

- Arithmetic Operators
- Assignment Operators
- Comparison Operators
- Logical Operators
- Conditional Operators
- Type Operators

### Arithmetic Operators

Arithmetic operators are used to perform arithmetic on numbers:

| Operator | Description |
| -------- | --------- |
| + | Addition |
| - | Subtraction |
| * | Multiplication |
| ** | Exponentiation |
| / | Division |
| % | Modulus (Division Remainder) |
| ++ | Increment |
| -- | Decrement |

### Assignment Operators

| Operator | Example |
--------- | -------- |
= | x = y
+= | x = x + y
-= | x = x - y
*= | x = x * y
/= | x = x / y
%= | x = x % y
**= | x = x ** y

### Comparison Operators

Operators | Description
--------- | ----------
== | equal to
=== | equal value and equal type
!= | not equal
!== | not equal value or not equal type
`>` | greater than
< | less than
`>=` | greater than or equal to
<= | less than or equal to
? | ternary operator

### Logical Operators

Operators | Description
------ | ---------
`&&` | logical AND
`II` | logical OR
`!` | logical NOT

JS operator: `&&` Logical AND

- true `&&` true —> true
- false `&&` true —> false
- true `&&` false —> false
- false `&&` false —> false

JS operator: `||` Logical OR

- Either side has to be true
- true `||` false —> true
- false `||` true —> true

## [Expressions and Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)

The above link is a detailed reference to JavaScript **expressions** and **operators**. An expression is a valid unit of code that resolves to a value.

## [Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)

The above link is a detailed reference to **functions** which are the basic building blocks in JavaScript. A function is a set of statements that perform/execute a task or calculate a value.
