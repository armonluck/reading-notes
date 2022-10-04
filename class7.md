# Class 7 Notes - *Programming with JavaScript*

## Control Flow

The ***control flow*** is the order in which a computer executes/runs statements in a script. 

Code is typically executed/ran from the first line in a file down to the last line. Exceptions to this rule are infrequent but include structures that change the control flow such as *conditionals* and *loops*.

An example of this exception can occur when a user is entering data on a webpage form. If a user attempts to *submit* data, but has left a required field empty (usually denoted by an asterisk), then the script will stop and prompt the user to fill in the missing information. A **conditional** structure or `if...else` statement is used in this case so that different code is executed depening on whether necessary information has been completed or not. 

> Example: 
`if (isEmpty(field)) {
    promptUser();
} else {
    submitForm();
}`