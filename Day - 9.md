# Day 9 – Python `while` Loop

Today I learned about the **`while` loop** and different loop control statements in Python.

## Topics Covered
Google Colab link : https://colab.research.google.com/drive/1P3nwZrREc3AC5FmVEV2QCTcCYupS5JK6?usp=sharing
### 1. `while` Loop

* A `while` loop executes as long as a condition is `True`.
* The condition is checked before every iteration.
* It is useful when the number of iterations is not known in advance.
* The loop variable must be updated to avoid an infinite loop.

**Example:**

```python
x = 0
while x <= 10:
    print(x)
    x += 2
```

---

### 2. Infinite Loop

* An infinite loop occurs when the condition never becomes `False`.
* Example:

```python
while True:
    print("This runs forever")
```

* Infinite loops are commonly used in games, servers, and continuous input programs.

---

### 3. `break` Statement

* The `break` statement immediately exits the loop.
* It is used when the required result is found and there is no need to continue.

---

### 4. `continue` Statement

* The `continue` statement skips the current iteration and moves to the next iteration.
* It does not terminate the loop.

---

### 5. `pass` Statement

* The `pass` statement does nothing.
* It is used as a placeholder when code will be added later.

---

### 6. Nested Loops

* A nested loop is a loop inside another loop.
* For every iteration of the outer loop, the inner loop executes completely.
* Nested loops are commonly used for patterns, multiplication tables, and working with matrices.

---

## Programs Practiced

* Printed even numbers using a `while` loop.
* Incremented values using `x += 2`.
* Counted backwards using a `while` loop.
* Understood how loop conditions control execution.

## Key Takeaways

* Learned when to use a `while` loop instead of a `for` loop.
* Understood the importance of updating the loop variable.
* Learned the difference between `break`, `continue`, and `pass`.
* Understood how nested loops work.

**Day 9 Status:** ✅ Completed
