# Module 2: Basic Operators
## Arithmetic Operators
Used for mathematical calculations.
```python
x = 10
y = 3
```
**Addition.** Add two values together.
```python
addition = x + y
> 13
```
**Subtraction.** Minus one value from another.
```python
subtraction = x - y 
> 7
```
**Multiplication.** Times one value by another
```python
multiplication = x * y
> 30
```
**Divsion.** Divide one value by another.
```python
division = x / y 
> 3.333333333333333
```
**Modulus.** Find the remainder of a divsion.
```python
modulus = x % y
> 1
```
**Exponentiation**. One value to the power of another.
```python
exponentiation = x ** y # Exponentiation
> 1000
```
---
## Comparison Operators
```python
x = 5
y = 6
```
**Equal to.** Checks if two values are equal.
```python
result = x == y
> False
```
**Not equal to.** Checks if two values are not equal.
```python
result = x != y
> True
```
**Greater than.** Checks if the value on the left is greater than the value on the right.
```python
result = x > y
> False
```
**Less than.** Checks if the value on the left is less than the value on the right.
```python
result = x < y
> True
```

**Greater than or equals to.** Checks if the value on the left is greater than or equal to the value on the right.
```python
result = x >= y
> True
```
**Less than or equals to.** Checks if the value on the left is less than or equal to the value on the right.
```python
result = x <= y
> False
```
### Chained Comparison Operators:
Chained comparisons are a concise way to make multiple comparisons in a single line.
```python
x = 5
y = 6
z = 7
```
```python
result = x > y < z
> False
```
```python
result = x <= y < z
> True
```

---
## Logical Operators
Used for logical operations (and, or, not).
```python
p = True
q = False
 ```
**AND Operator.** The `and` operator returns `True` only if both operands are true. If any one of the operands is false, the result is `False`.
 ```python
logical_and = p and q 
> False
```
**OR Operator** The `or` operator returns `True` if at least one of the operands is true. If both operands are false, the result is `False`.
```python
logical_or = p or q
> True
```
**NOT Operator** The `not` operator is a unary operator that returns the opposite of the operand's boolean value. If the operand is `True`, `not` returns `False`, and vice versa.
```python
logical_not = not p 
> False
```
Example of using logical operators in a conditional statement:
```python
age = 25
income = 50000

# Using logical AND and OR in a conditional statement 
if age > 18  and income > 30000:
	print("Eligible for a loan")
else:
	print("Not eligible for a loan")
```
---
## Membership Operators 
Used to test if a value is a member of a sequence (e.g., strings, lists, tuples).
```python
fruits = ['apple', 'banana', 'orange']
```
**Membership test.**
```python
is_apple_in_fruits = 'apple'  in fruits
> True
```
**Negated membership test.**
```python
not_berry_in_fruits = 'berry'  not  in fruits
> True
```
---
