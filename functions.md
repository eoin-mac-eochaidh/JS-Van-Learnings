# Javascript functions

## **Hoisting**
> JavaScript Hoisting refers to the process whereby the interpreter appears to move the declaration of functions, variables, classes, or imports to the top of their scope, prior to execution of the code.
Ref. https://developer.mozilla.org/en-US/docs/Glossary/Hoisting

> Function hoisting only works with function declarations — not with function expressions. The following code will not work:

So what this means, and what may bring confusion is that a function declaration like the following works.
```
console.log(functionMult(5));

functionAlpha(num){
    return (num *5 )
}
```

Where the following will not
```
console.log(square(5)); // ReferenceError: Cannot access 'square' before initialization
const square = function (n) {
  return n * n;
};
```

TO DO 
Use cases for function expressions and functions expressions. Strengths, weaknesses etc

## **Recursion**

A function can refer to and call itself.

A function that calls itself is called a recursive function

Much like a loop it needs some sort of a condition that will avoid an infinite running.
This is the **Base Case**. A condition where the function returns value without making the recursive call.

A **Recursive Case** will follow this, under which the function calls itself, returning an output.

The class iterative loop of recursive function approach both have their strengths.

Classic approach may be more readable and possibly easier to debug as steps are clearly visible.

Recursive approach may be shorter code

Useful for certain tasks like traversing linked lists and certain data structures, like linked lists, binary trees and graphs.

Recursive functions are a core element of the functional programming approach



