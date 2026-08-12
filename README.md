# Missing Number

## Explanation

The Missing Number problem requires finding the missing number from an array containing `n` distinct numbers taken from the range `0` to `n`.

For example:

```text
Input:
[3, 0, 1]

Output:
2
```

The numbers from `0` to `3` are `0, 1, 2, 3`. The number `2` is missing.

## Problem Statement

Given an array containing `n` distinct numbers in the range `0` to `n`, return the only number that is missing from the array.

## Features

* Finds the missing number
* Uses the mathematical sum formula
* Single array traversal
* Does not require an additional data structure
* Efficient solution

## How It Works

The program calculates the expected sum of numbers from `0` to `n` using:

```text
n × (n + 1) / 2
```

It then calculates the actual sum of all elements in the array.

The difference between the expected sum and actual sum gives the missing number.

```text
Missing Number = Expected Sum - Actual Sum
```

## Technologies Used

* Arrays
* Loops
* Mathematical operations
* Methods
* Conditional logic

## Data Structure Used

The program uses an integer array.

No additional data structure is required.

## Methods Used

### missingNumber()

Calculates and returns the missing number.

### main()

Creates the sample input, calls `missingNumber()`, and displays the result.

## Program Flow

```text
Start
↓
Read array
↓
Find array length
↓
Calculate expected sum
↓
Calculate actual sum
↓
Subtract actual sum from expected sum
↓
Return missing number
↓
Display result
↓
End
```

## Sample Input

```text
nums = [3, 0, 1]
```

## Sample Output

```text
Missing Number: 2
```

## Time Complexity

```text
O(n)
```

The array is traversed once.

## Space Complexity

```text
O(1)
```

Only a few variables are used.

## Key Learning

This problem teaches how a mathematical formula can be combined with array traversal to find a missing value efficiently.

## File Location

```text
Arrays/MissingNumber.java
```

## Repository Structure

```text
Missing-Number/
├── README.md
└── Arrays/
    └── MissingNumber.java
```

## Author

**V.Harini**
