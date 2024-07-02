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



