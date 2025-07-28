# Interview Assignment – Task 2

**Name:** Advithi Alva  
**College:** Sahyadri College of Engineering and Management (SCEM)  

---

##  Task Overview

This repository includes my solutions for Task 2 of the interview assignment. I've used Python to solve two array-based problems.

---

## Tools Used
- Language: Python 3
- No external libraries were used.
---


## Problem 1: Check for Duplicates

> **Objective:**  
> Given an array of integers, determine if any value appears at least twice.  
> If any integer appears more than once, return `True`. If every element is unique, return `False`.

### Test Case Results:

| Input                   | Expected Output | Actual Output | Result |
| ----------------------- | --------------- | ----------- | ------ |
| `[1, 2, 3, -1]`          | `False`         | `False`     | Pass   |
| `[1, 2, -3, 4]`          | `False`          | `False`      | Pass   |
| `[1, 1, 1, 3, 3, 4, 3, 2, 4, 2]`  | `True` | `True`      | Pass   |
| `[0, 0, 0, 1]`          | `True`         | `True`     | Pass   |



---

## Problem 2: Move Zeroes to End

> **Objective:**  
> Given an array of integers, move all `0`s to the end of the array while keeping the relative order of non-zero elements the same.  
> Must be done in-place, without creating a new copy of the array.

### Test Case Results:

| Input              | Expected Output    | Actual Output        | Result |
| ------------------ | ------------------ | ------------------ | ------ |
| `[0, 1, 0, 3, 12]` | `[1, 3, 12, 0, 0]` | `[1, 3, 12, 0, 0]` | Pass   |
| `[1, 2, 3, 4]`     | `[1, 2, 3, 4]`     | `[1, 2, 3, 4]`     | Pass   |
| `[0, 0, 0, 0]`     | `[0, 0, 0, 0]`     | `[0, 0, 0, 0]`     | Pass   |

---
## File Structure

```
├── problem1.py           
├── problem1_test.py     
├── problem2.py          
├── problem2_test.py      
```

Each problem is written in a separate `.py` file, and added its test cases in another file with a similar name. 

---

