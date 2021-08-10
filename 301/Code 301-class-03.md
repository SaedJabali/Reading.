# React

## Lifting State Up

In React, sharing state is accomplished by moving it up to the closest common ancestor of the components that need it. This is called “lifting state up”.

## Lists and Keys

First, let’s review how you transform lists in JavaScript.
Given the code below, we use the map() function to take an array of numbers and double their values. We assign the new array returned by map

() to the variable doubled and log it:

const numbers = [1, 2, 3, 4, 5]; const doubled = numbers.map((number) => number * 2); console.log(doubled); 

This code logs [2, 4, 6, 8, 10] to the console.

In React, transforming arrays into lists of elements is nearly identical.

## The Spread Operator

JavaScript operators are used to assign values, compare values, perform arithmetic operations, and more.

Spread syntax can be used when all elements from an object or array need to be included in a list of some kind.

The spread syntax “spreads” the array into separate arguments.

In *JavaScript*, spread syntax refers to the use of an **ellipsis** of three dots (. . .) to expand an iterable object into the list of arguments.
