# [Home](../../README.md)
# Day 03
## A beginner's guide to Big O Notation

>What is the Big O notation:

Big O notation is used in Computer Science to describe the performance or complexity of an algorithm. Big O specifically describes the worst-case scenario, and can be used to describe the execution time required or the space used (e.g. in memory or on disk) by an algorithm.

>Cases of Big O notation

![time-complixity](../../asset/time-complexity.png)

1- O(1)

O(1) describes an algorithm that will always execute in the same time (or space) regardless of the size of the input data set.

>Example

x=5*3+2

2- O(N)

O(N) describes an algorithm whose performance will grow linearly and in direct proportion to the size of the input data set. The example below also demonstrates how Big O favours the worst-case performance scenario; a matching string could be found during any iteration of the for loop and the function would return early, but Big O notation will always assume the upper limit where the algorithm will perform the maximum number of iterations.

>Example

for loop

3- O(N²)

Represents an algorithm whose performance is directly proportional to the square of the size of the input data set. This is common with algorithms that involve nested iterations over the data set. Deeper nested iterations will result in O(N³), O(N⁴) etc.

>Example

nested for loop


4- O(2^N)

O(2^N) denotes an algorithm whose growth doubles with each addition to the input data set. The growth curve of an O(2^N) function is exponential — starting off very shallow, then rising meteorically.

>Example

The recursive calculation of Fibonacci numbers

5- Logarithms

I didn't understand it

> ## Referances

1- https://rob-bell.net/2009/06/a-beginners-guide-to-big-o-notation

2- https://www.youtube.com/watch?v=__vX2sjlpXU