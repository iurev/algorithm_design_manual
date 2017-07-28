# Chapter 1 - algorithms complexity

Two most often considered measurement of algorithms — **time complexity** and **space complexity**.

## Time complexity

**worst** – ```O(f(n))```, read as _big-o_, the most widely used

**medium** – ```Θ(fn(n))```, read as _big-theta_

**best** – ```Ω(f(n))```, read as _big-omega_, rarely used in practice

For example:  ```O(lg(n))```

**Comparation of time complexities:**

![img](http://3.bp.blogspot.com/-2LIuuPw6s7U/VjNdKJe9NpI/AAAAAAAAAB8/hs-VgNQmyVY/s1600/Best_Worst_Avg.jpg "asdf")

Approximations are used much more often than exact measurements.

For example, these two functions are treated as equal ```O(n^2)``` == ```O(25.7 * n^10)```.

Hidden constant – is all hidden values inside ```O(...)```.

**Comparation of time complexity functions:**

![img](https://therecyclebin.files.wordpress.com/2008/05/time-complexity.png)

## Useful links:
[wikipedia — Analysis of algorithms](https://en.wikipedia.org/wiki/Analysis_of_algorithms)
