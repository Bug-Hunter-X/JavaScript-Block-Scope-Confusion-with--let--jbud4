# JavaScript Block Scope Gotcha

This repo demonstrates a common point of confusion for JavaScript developers: block scope and the `let` keyword.

The `bug.js` file contains code that might behave unexpectedly if you're not familiar with how `let` creates block-scoped variables.  The `bugSolution.js` file is intentionally left blank, as the bug is in the understanding and not a syntax error.  The solution is simply understanding how block scoping works in Javascript using the let keyword.

## Understanding the Bug

The key is to pay attention to where the `let` keyword is used. Variables declared with `let` are only accessible within the block of code they are declared in (the code enclosed in curly braces `{}`).