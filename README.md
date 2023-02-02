# Welcome to My Bc
***

## Task
Write a programm called my_bc. 
You can test your code against memory errors by compiling with the debugging flags -g3 -fsanitize=address

## Description
A valid expression:

• must only contain the operators +, -, *, /, and modulo (percent)
• must only have integer values
• can contain parentheses, but each group must be properly closed
• can contain spaces
Since we are doing whole number arithmetic, divisions are euclidian keeping only the quotient, while the remainder can be obtained with a modulo operation.

## Installation
 Makefile

## Usage

```
Make 
./my_bc "1 + 2 * (3 - 42) / 5"

```
