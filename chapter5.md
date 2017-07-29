# Chapter 5 - Combinatorial search and heuristics methods

## Backtracking
**Backtracking** constructs a tree of partial solutions until algorithm finds out that this solution is wrong or right.
Technique, when algorithm stops searching down the tree if any children nodes are evidently wrong is called **search pruning**.

Applications:
- traveling salesman
- schedule optimization
- robotics
- AI
- mind games like chess and even go
- puzzles like crosswords, sudoku

## Heuristics

> is any approach to problem solving, learning, or discovery that employs a practical method not guaranteed to be optimal or perfect, but sufficient for the immediate goals

### Simulated annealing
**Search space** is set of all possible solutions.

**Simulated annealing** is a technique for searching approximate global minimum/maximum. Often used when search space is discrete.

![Simulated annealing visualization](https://upload.wikimedia.org/wikipedia/commons/d/d5/Hill_Climbing_with_Simulated_Annealing.gif)

Three components:

– concise problem representation – search space and **cost function**
– transitions – how to move from one state to another one
– cooling schedule – which tells algorithm that it has to gamble less

### Neural networks
Can be applied to solve combinatorial problems, but simulated annealing is more preferred.

### Genetic algorithms
Author don't recommend using them in practice because they're the less effective ones.

### Parallel algorithms
They can speed your algorithm up, but they also introduce you to many other types of problems.

## Useful links:

[slideshare.net – BackTracking Algorithm: Technique and Examples](https://www.slideshare.net/FahimFerdous6/backtracking-algorithm-technique-and-examples)

[wikipedia.org – Backtracking](https://en.wikipedia.org/wiki/Backtracking)

[lesswrong.com – Search space](https://wiki.lesswrong.com/wiki/Search_space)

[quora.com – Is simulated annealing a Monte Carlo method?](https://www.quora.com/Is-simulated-annealing-a-Monte-Carlo-method)

[coursera.org – Machine Learning](https://www.coursera.org/learn/machine-learning)

