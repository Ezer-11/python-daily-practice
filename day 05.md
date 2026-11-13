# Day 05 — Python Practice Questions (logic building)

## Q1. Count Different Character Type

Take a string and count:
- Uppercase letters
- Lowercase letters
- Digits
- Special characters

Spaces should not count in any category.

**Input:**
```text
Hello123! Python
```

**Output:**
```text
Uppercase: 2
Lowercase: 9
Digits: 3
Special characters: 1
```

## Q2. Print a Number Triangle

Take an integer `n` and print the following pattern.

**Input:**
```text
5
```

**Output:**
```text
1
12
123
1234
12345
```

## Q3. Find Common Elements in Two Lists

Take two integer lists and print their common distinct elements in the order they first appear in the first list.

**Input:**
```text
6
1 2 3 2 4 5
5
2 4 6 2 1
```

**Output:**
```text
2 4 1
```

**Requirements:**
- Do not use set intersection.
- Do not print duplicate common elements.
- Preserve the order from the first list.

## Q4. Check Whether a List Is a Palindrome

A list is a palindrome if it reads the same forward and backward.

Determine whether the given list is a palindrome.

**Input:**
```text
5
1 2 3 2 1
```

**Output:**
```text
Palindrome
```

**Another Example — Input:**
```text
4
1 2 3 4
```

**Output:**
```text
Not Palindrome
```

**Requirements:**
- Do not use `reverse()`.
- Do not use slicing (`[::-1]`).
- Try comparing elements using indexes from both ends.

## Q5. Find the GCD Using a Function

Write a function called `gcd(a, b)` that returns the greatest common divisor of two non-negative integers.

The GCD is the largest positive integer that divides both numbers exactly.
