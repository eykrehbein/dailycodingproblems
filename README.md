# Daily Coding Problem Solutions

Hi! In this personal project, I am solving logical programming tasks/questions, provided by [DailyCodingProblem](https://www.dailycodingproblem.com).

## Tasks

### #1

[Solution (Jupyter Notebook)](#1.ipynb)

> This problem was recently asked by Google.

Given a list of numbers and a number `k`, return whether any two numbers from the list add up to `k`.
_For example_, given `[10, 15, 3, 7]` and `k = 17`, return true since `10 + 7` is `17`.

### #2

[Solution (Jupyter Notebook)](#2.ipynb)

> This problem was asked by Uber.

Given an array of integers, return a new array such that each element at index `i` of the new array is the product of all the numbers in the original array except the one at `i`.

_For example_, if our input was `[1, 2, 3, 4, 5]`, the expected output would be `[120, 60, 40, 30, 24]`. If our input was `[3, 2, 1]`, the expected output would be `[2, 3, 6]`.

_Follow-up_: what if you can't use division?

### #3

[Solution (Jupyter Notebook)](#3.ipynb)

> This problem was asked by Stripe.

Given an array of integers, find the first missing positive integer in linear time and constant space. In other words, find the lowest positive integer that does not exist in the array. The array can contain duplicates and negative numbers as well.

_For example_, the input `[3, 4, -1, 1]` should give `2`. The input `[1, 2, 0]` should give `3`.

You can modify the input array in-place.
