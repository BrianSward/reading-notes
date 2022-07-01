# Read: 08 - Operators and Loops

## Assignment

- [Expressions and Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
  - Focus only on Comparison operators and Assignment operators.
- [Loops](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)
  - Focus only on for statement and while statement loops.

## Submission

### Expressions and Operators

- Assignment operators
An assignment operator assigns a value to its left operand based on the value of its right operand. or
    x = f() is an assignment expression that assigns the value of f() to x.

There are also compound assignment operators (see reading for URL to list if this is confusing)

- Assignment: x = f() => _x = f()_
- Addition assignment: x += f() _x = x + f()_
- Subtraction assignment x -= f() _x = x - f()_
- Multiplication assignment x *= f() _x = x * f()_
- Division assignment x /= f() _x = x / f()_
- Remainder assignment x %= f() _x = x % f()_
- for more please see reading assignment as they were breaking things
- Indexing seems to start at 0

- chaining or nesting an assignment expression, its result can itself be assigned to another variable.

**When chaining these expressions without parentheses or other grouping operators like array literals, the assignment expressions are grouped right to left (they are right-associative), but they are evaluated left to right.**

- Comparison operators
A comparison operator compares its operands and returns a logical value
  - Equal (==) Returns true if the operands are equal.
  - Not equal (!=) Returns true if the operands are not equal
  - Strict equal (===) Returns true if the operands are equal and of the same type.
  - Strict not equal (!==) Returns true if the operands are of the same type but not equal, or are of different type.
  - Greater than (>) Returns true if the left operand is greater than the right operand.
  - Greater than or equal (>=) Returns true if the left operand is greater than or equal to the right operand.
  - Less than (<) Returns true if the left operand is less than the right operand.
  - Less than or equal (<=) Returns true if the left operand is less than or equal to the right operand

ProTip - ! is just math/logic not (man i wish i knew that earlier)

### Loops

-Loops and iteration
Loops offer a quick and easy way to do something repeatedly. This chapter of the JavaScript Guide introduces the different iteration statements available to JavaScript.

You can think of a loop as a computerized version of the game where you tell someone to take X steps in one direction, then Y steps in another. For example, the idea "Go five steps to the east" could be expressed this way as a loop:

There are many different kinds of loops, but they all essentially do the same thing: they repeat an action some number of times. (Note that it's possible that number could be zero!)

The statements for loops provided in JavaScript are:

for statement
do...while statement
while statement
labeled statement
break statement
continue statement
for...in statement
for...of statement

We examine for and while statements

#### For Statements

- These go until a certain condition is met, (i arriving at 10 or whathaveyou)
- SYNTAX for ([initialExpression]; [conditionExpression]; [incrementExpression])
  - initialExpression, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.
  - conditionExpression expression is evaluated. If the value of conditionExpression is true, the loop statements execute. Otherwise, the for loop terminates.
  - The statement executes. To execute multiple statements, use a block statement ({ ... }) to group those statements.
If present, the update expression incrementExpression is executed.

- In JavaScript the for statement declares the variable i and initializes it to 0. It checks that i is less than the number of options in the select element, performs the succeeding if statement, and increments i by 1 after each pass through the loop.

#### While Statements

while statement
A while statement executes its statements as long as a specified condition evaluates to true. that is to say while true it will loop, when false it ends

To execute multiple statements, use a block statement ({ ... }) to group those statements.

Avoid infinite loops. Make sure the condition in a loop eventually becomes false—otherwise, the loop will never terminate!

[Homepage](https://briansward.github.io/reading-notes/)
