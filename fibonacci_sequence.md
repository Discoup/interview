# The Fibonacci Sequence

The Fibonacci sequence appears in nature all around us, in the arrangement of seeds in a sunflower and the spiral of a nautilus for example.

The Fibonacci sequence begins with $Fib_0 = 0$ and $Fib_1 = 1$ as its first and second terms. After these first two elements, each subsequent element is equal to the sum of the previous two elements.

This series can be broken down as the following series:

$$
\begin{align*}
&Fib_0 = 0 \\
&Fib_1 = 1 \\
&Fib_n = Fib_{n-1} + Fib_{n-2}\ \ (n > 1)\\
\end{align*}
$$

First few elements of Fibonacci series are: $0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144, 233, 377...$

You are given a list of non-negative integers. For each integer, $n$, in the list print $n^{th}$ fibonacci number modulo $10^8+7$.

## Input Format

The first line contains an integer $T$, denoting the number of test-cases. $T$ lines follow, each representing a test case. In each line there is a non-negative integer, $n$.

## Output Format

For each test case, print $Fib_n\ \% \ (10^8+7)$.

## Constraints

$1 <= T <= 104$

$0 <= n <= 104$

## Sample Input #0

```
5
0
1
5
10
100
```

## Sample Output #0

```
0
1
5
55
24278230
```