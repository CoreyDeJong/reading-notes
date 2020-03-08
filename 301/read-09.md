## Concepts of Functional Programming in Javascript
 - Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data
1. Pure Functions
* returns the same result if given the same arguments
* it does not cause any observable side effects
 - if our function reads external files, it’s not a pure function — the file’s contents can change.
 - Any function that relies on a random number generator cannot be pure.
 - Benefits of the code is easier to test.
2. Immutability
* unchanging over time or unable to be changed 

Higher-order functions
* When we talk about higher-order functions, we mean a function that either:
 - takes one or more functions as arguments, or
 - returns a function as its result

## Refactoring JavaScript for Performance and Readability
 - Return early from functions
 - Cache variables so functions can be read like sentences
 - Check for Web APIs before implementing your own functionality