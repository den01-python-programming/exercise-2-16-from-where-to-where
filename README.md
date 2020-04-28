# Exercise 2.16 From where to where

## Where to

Write a program which prints the integers from 1 to a number given by the user.

```plaintext
Where to? **3**
1
2
3
```

```plaintext
Where to? **5**
1
2
3
4
5
```

**Hint:** The number read from the user is now the upper limit of the condition. Remember that in Python `a <= b` means _a is smaller or equal to b_.

## Where from

Ask the user for the starting point as well.

```plaintext
Where to? **8**
Where from? **5**
5
6
7
8
```

If the upper limit is larger than the starting point, nothing is printed:

```plaintext
Where to? **12**
Where from? **16**
```

**NB:** Remember that the lower and upper limits can be negative!
