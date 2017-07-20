# Chapter 1 - algorithm complexity

Two most often considered measurement of algorithms – **time complexity** and **space complexity**.

## Time complexity

**worst** – ```O(f(n))```, read as _big-o_, the most widely used

**medium** – ```Θ(fn(n))```, read as _big-theta_

**best** – ```Ω(f(n))```, read as _big-omega_, rarely used in practice

For example:  ```O(lg(n))```

**Comparation of time complexities:**

![img](http://3.bp.blogspot.com/-2LIuuPw6s7U/VjNdKJe9NpI/AAAAAAAAAB8/hs-VgNQmyVY/s1600/Best_Worst_Avg.jpg "asdf")

Designers often use approximations, not real values.

For example, these two functions are treated as equal ```O(n^2)``` == ```O(n^10)```.

**Comparation of time complexity functions:**

![img](https://therecyclebin.files.wordpress.com/2008/05/time-complexity.png)
