[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/W5H3Dnce)
# Experiment 25: Bubble Sort Stats

## Problem Statement

Perform **Bubble Sort** on an array of integers and print three values:
1. Number of swaps it took to sort the array.
2. The first element after sorting.
3. The last element after sorting.

## Input Format

* The first line contains an integer $n$.
* The second line contains $n$ space-separated integers.

## Output Format

Print the required three values, each on a new line.

### Example 1

**Input:**

```text
3
6 4 1
```

**Output:**

```text
3
1
6
```

### Explanation

* **Original:** [6, 4, 1]
* **Pass 1:**
  * Swap 6,4 -> [4, 6, 1]
  * Swap 6,1 -> [4, 1, 6]
  * (Swaps: 2)
* **Pass 2:**
  * Swap 4,1 -> [1, 4, 6]
  * (Swaps: 1)
* **Total Swaps:** 3
* **Sorted Array:** [1, 4, 6] -> First: 1, Last: 6
