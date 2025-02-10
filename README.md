# TypeScript Type Error: Type 'string' is not assignable to type 'number'

This repository demonstrates a common TypeScript type error and its solution.

## The Bug

The `add` function is designed to add two numbers. However, the provided example attempts to add a number and a string, leading to a type error.

## The Solution

The solution involves using type guards or input validation to ensure both inputs are numbers before performing the addition. The improved version of the add function provides additional type checking.