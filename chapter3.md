# Chapter 3 - common design paradigms

- Divide and conquer
- Dynamic programming
- Greedy algorithm
- Back Tracking
- Brute Force

## Dynamic programming

It's a technique of speeding up recurrent algorithms.

It's **applicable** in case when:

- it's recurrent
- it has overlapping problems
- input is ordered

**Downsides:**

- still have not much meaning in solving NP-complete problems
- we don't know sequence which lead us to the result

### ~~Dynamic programming vs memoization~~
From [stackoverflow.com](https://stackoverflow.com/a/21145925)
> So **Dynamic programming** is a method to solve certain classes of problems by solving recurrence relations/recursion and storing previously found solutions via either **tabulation** or **memoization**.

> **Memoization** is a method to keep track of solutions to previously solved problems and can be used with any function that has unique deterministic solutions for a given set of inputs.

### Memoization
When you use memoization you store your data in key-value based data structures.

### Tabulation
With tabulation you store all results in a table (array) with index-based access to data.

## Divide and conquer

It's a technique of solving algorithms through separating input on two or more parts.

For example, _merge sort_, _MapReduce_.

## Randomization

Some algorithms use random numbers to solve problems. Correctness of using it is proven using statistics.

For example, _quick sort_, _fast exponentiation_.

## To be continued in the next chapters
- Greedy algorithm
- Back Tracking
- Brute Force

## Useful links:

[stackoverflow.com – What is the difference between memoization and dynamic programming?](https://stackoverflow.com/questions/6184869/what-is-the-difference-between-memoization-and-dynamic-programming)

[stackexchange.com – Is MapReduce anything more than just an application of divide and conquer?](https://softwareengineering.stackexchange.com/questions/98800/is-mapreduce-anything-more-than-just-an-application-of-divide-and-conquer)

[wikipedia – Divide and conquer](https://en.wikipedia.org/wiki/Divide_and_conquer_algorithm)

[khanacademy.org - Divide and conquer algorithms](https://www.khanacademy.org/computing/computer-science/algorithms/merge-sort/a/divide-and-conquer-algorithms)

[wikipedia - Randomization](https://en.wikipedia.org/wiki/Randomization)

[wikipedia – Dynamic programming](https://en.wikipedia.org/wiki/Dynamic_programming)

[wikipedia – Memoization](https://en.wikipedia.org/wiki/Memoization)

