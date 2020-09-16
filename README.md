# S-expression-integer-calculator

This code takes a string type argument as a function call and returns the evaluation as an integer.
A function call takes the following form: (FUNCTION EXPR EXPR)
A function call is always delimited by parenthesis ( and ).
The FUNCTION is one of add, subtract, multiply or power.
The EXPR can be any arbitrary expression, i.e. it can be further function calls or integer expressions. 
Since this is an integer calculator, the exponent of the power function should be a non-negative integer. 
Exactly one space is used to separate each term.

Note: This code works as long as the call starts and ends with ( and ). Extra parentheses embodying the call are ignored, e.g. calculator('((((((add (multiply 2 3) 2)))')
