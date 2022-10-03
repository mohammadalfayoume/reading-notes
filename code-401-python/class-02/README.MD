# [Home](../../README.md)
# Day 02
## In Tests We Trust — TDD with Python

### Unit tests and TDD?
Unit tests are some pieces of code to exercise the input, the output and the behaviour of your code. You can write them anytime you want.

TDD: Test-Driven Development is a strategy to think (and write!) tests first.

### Benifits of TDD:
* The greatest advantage about TDD is to craft the software design first.
* Your code will be more reliable: after a change you can run your tests and be in peace.
* Beginning may be hard — and that’s fine. You just need to practice!

## What does the if __name__ == “__main__”: do?

If the python interpreter is running that module (the source file) as the main program, it sets the special __name__ variable to have a value “__main__”. If this file is being imported from another module, __name__ will be set to the module’s name. Module’s name is available as value to __name__ global variable. 

This is it, if __name__ == '__main__' is useful to import a Module to use the functions inside of it, without running the script.

## Introduction to Recursion – Data Structure and Algorithm Tutorials

The process in which a function calls itself directly or indirectly is called recursion and the corresponding function is called a recursive function. Using a recursive algorithm, certain problems can be solved quite easily. 

A recursive function solves a particular problem by calling a copy of itself and solving smaller subproblems of the original problems. Many more recursive calls can be generated as and when required. It is essential to know that we should provide a certain case in order to terminate this recursion process. So we can say that every time the function calls itself with a simpler version of the original problem.

Recursion is an amazing technique with the help of which we can reduce the length of our code and make it easier to read and write.

### Properties of Recursion:

* Performing the same operations multiple times with different inputs.

* In every step, we try smaller inputs to make the problem smaller.

* Base condition is needed to stop the recursion otherwise infinite loop will occur.

> # Referances

1) https://code.likeagirl.io/in-tests-we-trust-tdd-with-python-af69f47e6932

2) https://www.geeksforgeeks.org/what-does-the-if-__name__-__main__-do/

3) https://www.geeksforgeeks.org/recursion/