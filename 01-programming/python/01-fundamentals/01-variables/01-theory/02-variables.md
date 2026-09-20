# Variables

## Overview

Variables are one of the most fundamental concepts in Python and every other programming language.

They allow programs to store information using meaningful names instead of working directly with raw values. Once a value is stored in a variable, it can be reused, modified, and combined with other values throughout the program.

In this lesson, you will learn how to create variables, how assignment works, and how to choose clear and descriptive names.

---

## Learning Objectives

After completing this lesson, you will be able to:

- Create variables in Python.
- Understand the assignment operator (`=`).
- Assign different types of values.
- Reassign variables.
- Follow Python naming conventions.
- Write more readable and maintainable code.

---

# What Is a Variable?

A variable is a **name that refers to a value**.

Instead of using values directly throughout a program, we give them meaningful names.

For example:

```python
age = 25
```

Here:

- `age` is the variable.
- `25` is the value.
- `=` is the assignment operator.

You can now use `age` anywhere in your program.

```python
print(age)
```

Output:

```text
25
```

---

# The Assignment Operator

In mathematics, the symbol `=` means **is equal to**.

In Python, the symbol `=` means **assign this value to this variable**.

```python
city = "London"
```

This statement should be read as:

> Assign the value `"London"` to the variable `city`.

It does **not** mean:

> city equals London

The value on the right is assigned to the name on the left.

---

# Creating Variables

Creating a variable is simple.

```python
name = "Alice"
age = 30
height = 1.68
```

Python automatically determines the type of each value.

Unlike some programming languages, you do not need to declare the variable type.

---

# Using Variables

Variables can be used wherever a value is expected.

```python
name = "Alice"

print(name)
```

Output:

```text
Alice
```

Variables can also be combined.

```python
first_name = "Alice"
last_name = "Johnson"

print(first_name, last_name)
```

Output:

```text
Alice Johnson
```

---

# Reassigning Variables

Variables can receive new values.

```python
score = 10

print(score)

score = 20

print(score)
```

Output:

```text
10
20
```

The variable name stays the same.

Only its value changes.

---

# Variables Can Refer to Different Types

Python is dynamically typed.

A variable can refer to different types of values during execution.

```python
value = 10

value = "Hello"

value = True
```

Although this is allowed, changing the meaning of a variable unnecessarily usually makes code harder to understand.

---

# Multiple Assignment

Python allows assigning multiple variables in one statement.

```python
x, y, z = 10, 20, 30
```

You can also assign the same value to multiple variables.

```python
a = b = c = 0
```

Output:

```python
print(a, b, c)
```

```text
0 0 0
```

---

# Swapping Variables

Python provides a clean way to exchange values.

Instead of writing:

```python
temp = x
x = y
y = temp
```

You can simply write:

```python
x, y = y, x
```

Example:

```python
x = 5
y = 10

x, y = y, x

print(x)
print(y)
```

Output:

```text
10
5
```

---

# Variable Naming Rules

Variable names must follow Python's syntax rules.

A variable name:

- may contain letters
- may contain digits
- may contain underscores (`_`)
- cannot start with a digit
- cannot contain spaces
- cannot contain special characters

Valid examples:

```python
name
user_name
price2
total_amount
```

Invalid examples:

```python
2price
user-name
first name
total$
```

---

# Naming Conventions

Python follows the **snake_case** convention.

Good:

```python
student_name
total_price
account_balance
```

Avoid:

```python
StudentName
studentName
x
a
tmp1
```

Unless the variable is used in a very small scope.

---

# Meaningful Names

Good variable names describe their purpose.

Poor:

```python
a = 25
b = 80
```

Better:

```python
age = 25
exam_score = 80
```

Even better:

```python
student_age = 25
final_exam_score = 80
```

Readable code is easier to maintain.

---

# Constants

Python does not have true constants.

By convention, values that should not change are written using uppercase names.

```python
PI = 3.14159

MAX_USERS = 100

SECONDS_PER_DAY = 86400
```

This convention tells other developers that the value is intended to remain unchanged.

---

# Common Mistakes

## Using unclear names

Instead of:

```python
x = 1200
```

Prefer:

```python
monthly_salary = 1200
```

---

## Reusing variables for different purposes

Avoid:

```python
data = "Alice"

data = 25

data = True
```

Although valid, this makes programs difficult to understand.

---

## Confusing assignment with comparison

Incorrect:

```python
age = 18
```

This assigns a value.

Comparison uses:

```python
age == 18
```

You will learn about comparisons in the next module.

---

# Best Practices

- Use descriptive names.
- Keep names short but meaningful.
- Follow the snake_case convention.
- Avoid abbreviations unless they are well known.
- Do not reuse variables unnecessarily.
- Write code for humans first and computers second.

---

# Summary

Variables allow Python programs to store and reuse information.

Using meaningful names makes code easier to read, debug, and maintain.

Understanding assignment and naming conventions is an essential foundation for writing professional Python code.

---

# Key Takeaways

- Variables refer to values.
- The assignment operator (`=`) stores a value in a variable.
- Variables can be reassigned.
- Python uses dynamic typing.
- Good variable names improve readability.
- Python uses the snake_case naming convention.

---

## Next Lesson

In the next lesson, you will learn about Python's built-in data types and how different kinds of information are represented inside a program.
