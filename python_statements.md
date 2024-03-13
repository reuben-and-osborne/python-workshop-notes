# Module 2: Python Statements

In Python, statements are instructions that the Python interpreter can execute. Python offers several types of statements to *control the flow* of a program, make decisions, and iterate over data. Let's explore some of the fundamental statements in Python:

**If Statements:**

`if` statements allow you to execute a block of code only if a specified condition is true.

```python
if condition:
    # Code to be executed if condition is true
```

```python
x = 10

if x > 5:
    print("x is greater than 5")
```
---

**For Loops:**

`for` loops are used to iterate over a sequence (such as lists, tuples, or strings) and execute a block of code for each item in the sequence.

```python
for item in sequence:
    # Code to be executed for each item
```

```python
fruits = ["apple", "banana", "orange"]

for fruit in fruits:
    print(fruit)
```
---
**While Loops:**

`while` loops continue to execute a block of code as long as a specified condition is true.
```python
while condition:
    # Code to be executed while condition is true
```

```python
i = 1

while i <= 5:
    print(i)
    i += 1
```
---
**Range:**

The `range` function generates a sequence of numbers that can be used in `for` loops.

```python
range(start, stop[, step])
```

```python
for i in range(5):
    print(i)  # Output: 0, 1, 2, 3, 4
```
---
**List Comprehensions:**

List comprehensions provide a concise way to create lists based on existing lists or other iterable objects.

```python
[expression for item in iterable]
```


```python
numbers = [1, 2, 3, 4, 5]

squares = [x ** 2 for x in numbers]
print(squares)  # Output: [1, 4, 9, 16, 25]
```

---
