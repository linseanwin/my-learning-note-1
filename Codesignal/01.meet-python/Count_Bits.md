
Implement a function that, given an integer n, uses a specific method on it and returns the number of bits in its binary representation.

Note: in this task and most of the following tasks you will be given a code snippet with some part of it replaced by the ellipsis (...). Only this part is allowed to be changed.

Example

```
For n = 50, the output should be
countBits(n) = 6.
```

5010 = 1100102, a number that consists of 6 digits. Thus, the output should be 6.

* Input/Output
    - [time limit] 4000ms (py3)
    - [input] integer n

* A positive integer.

* Guaranteed constraints:
    - 1 ≤ n ≤ 109.

* [output] integer
    - The number of bits in binary representation of n.


**Answer:**

```python
def countBits(n):
    return n.bit_length()
```

bit_length()為一python的套件,用來取2進位後的數字長度
