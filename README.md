Fundamental_Lab3 

# Python Fundamentals – Lab 3

This repository contains my practice work for **Python Fundamentals – Lab 3**.

The main goal of this lab is to learn how Python programs make decisions and repeat tasks using **conditional statements and loops**.

This lab builds on the concepts from Lab 1 and Lab 2, including variables, strings, lists, dictionaries, and user input.

## Topics Covered

### Conditional Statements

Practised using:

```python
if
elif
else
```

Example:

```python
number = int(input("Enter a number: "))

if number > 0:
    print("Positive")
elif number < 0:
    print("Negative")
else:
    print("Zero")
```

This program checks whether a number is positive, negative, or zero.

## Age Group Checker

Practised using multiple conditions.

```python
age = int(input("Enter your age: "))

if age < 13:
    print("Child")
elif age < 18:
    print("Teenager")
elif age < 65:
    print("Adult")
else:
    print("Senior")
```

This exercise helped me understand how Python checks conditions from top to bottom.

## Grade Calculator

Created a simple grade calculator using `if`, `elif`, and `else`.

```python
score = int(input("Enter score: "))

if score >= 90:
    print("A")
elif score >= 80:
    print("B")
elif score >= 70:
    print("C")
elif score >= 60:
    print("D")
else:
    print("F")
```

## Comparison Operators

Practise Python comparison operators.

| Operator | Meaning                  |
| -------- | ------------------------ |
| `==`     | Equal to                 |
| `!=`     | Not equal to             |
| `>`      | Greater than             |
| `<`      | Less than                |
| `>=`     | Greater than or equal to |
| `<=`     | Less than or equal to    |

Exam
