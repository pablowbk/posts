---
title: ES6 features for beginners, like myself. Part 1
published: false
description: ES6 features that I was asked during a phone interview. Part 1 of 2
tags: es6, javascript, interview, beginners
---

Today I had a phone interview that went terribly bad. I wasn't focused nor prepared, at all. However, the interviewer was nice and we had a fun talk, despite my failed attempts to answer most of his questions.

So I wanted to write about **some ES6 features**, because I knew I've been using them, but just could not name any when the question was asked.

![alt text](https://images.pexels.com/photos/6301/fireworks-new-year-new-2015.jpg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940 "Photo of 2015 fireworks")

Little note about ES6, aka ECMAScript 2015. A **LOT** of features were introduced in this version, but I will just point out the ones that popped up during the interview. For a detailed list of all the new stuffed that was introduced, check out [this site](http://es6-features.org/).

Ok, let's dive right into it.

#### Arrow functions. 
Shorter syntax, one-line implicit return statement, lexical **this**. *Wait, what?*!
```javascript
const double = num => num + num; // in a one-line expression, return is implicit
// vs
const doubleFn = function(num) {
  return num + num;
}
```
>"An arrow function does not have its own **this**. The this value of the enclosing lexical scope is used."  More on [MDN's site](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions).

___

#### let, const
lorem
___
#### promise
#### spread operator
#### template literals
#### object shorthand properties
#### destructuring assignment
#### classes
#### recursion
