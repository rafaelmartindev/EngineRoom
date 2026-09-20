# Introduction

## Overview

Programming is the process of solving problems by giving precise instructions to a computer.

Every application you use—from a calculator to a banking system or an AI assistant—works by receiving, processing, storing, and producing information.

Before learning Python syntax, it is important to understand the role of information inside a program and why variables are one of the fundamental building blocks of software.

---

## Learning Objectives

After completing this lesson, you will be able to:

- Understand the purpose of variables in programming.
- Explain how programs work with information.
- Recognize why variables are essential in every programming language.
- Describe the relationship between variables and computer memory.

---

# What Is Programming?

A computer cannot think, make assumptions, or guess what we want to do.

It simply follows instructions.

A program is a sequence of instructions written in a programming language that tells the computer exactly what to do.

For example:

1. Read information.
2. Process that information.
3. Store intermediate results.
4. Produce an output.

This process happens millions of times every second in modern software.

---

# Information Is Everywhere

Think about the applications you use every day.

A messaging app stores:

- Your username
- Your contacts
- Your conversations

A weather application stores:

- Temperature
- Humidity
- Wind speed

An online store stores:

- Product names
- Prices
- Stock availability

An AI application stores:

- User prompts
- Model responses
- Conversation history

Although these applications are very different, they all have something in common:

They continuously store and update information.

---

# Why Variables Exist

Imagine writing a shopping list on a whiteboard.

Instead of rewriting the entire list every time something changes, you simply erase one item and write a new one.

Variables work in a similar way.

They allow programs to associate a name with a value so that the value can be reused and updated whenever necessary.

For example:

```python
price = 29.99
```

Instead of remembering the number `29.99`, the program remembers the name `price`.

Later, the value can change:

```python
price = 24.99
```

The variable keeps the same name, but now refers to a different value.

---

# Variables and Memory

When a program runs, it uses the computer's memory to store information.

You can think of memory as a collection of labeled boxes.

Each box has:

- a name
- a value

For example:

```text
+-----------+
|  age      |
+-----------+
|    25     |
+-----------+

+-----------+
|  name     |
+-----------+
|  Alice    |
+-----------+
```

When the program needs the value of `age`, it simply looks inside the corresponding box.

This is a simplified model, but it is a useful way to understand how variables behave.

---

# A First Python Example

```python
name = "Alice"
age = 25

print(name)
print(age)
```

Output:

```text
Alice
25
```

In this example:

- `name` refers to a text value.
- `age` refers to a numeric value.
- `print()` displays their values on the screen.

---

# Variables Make Software Flexible

Without variables:

```python
print("Hello, Alice!")
```

The program only works for Alice.

Using a variable:

```python
name = "Alice"

print(f"Hello, {name}!")
```

Changing the value changes the program's behavior without modifying its logic.

```python
name = "Rafael"
```

Output:

```text
Hello, Rafael!
```

This flexibility is one of the main reasons variables exist.

---

# Real-World Examples

Variables are used everywhere in software.

Examples include:

| Variable      | Possible Value |
| ------------- | -------------- |
| username      | `"john_doe"`   |
| balance       | `1250.75`      |
| temperature   | `21.4`         |
| is_logged_in  | `True`         |
| current_page  | `5`            |
| battery_level | `87`           |

Every modern application depends on thousands—or even millions—of variables while it is running.

---

# Common Misconceptions

### Variables are boxes.

Not exactly.

Thinking of variables as labeled boxes is useful for learning, but Python actually stores references to objects in memory. You will explore this concept later in the roadmap.

---

### Variables permanently store information.

No.

Variables only exist while the program is running unless their values are saved to a file or a database.

---

### Variables can only contain numbers.

False.

Variables can store many different kinds of data, including:

- text
- numbers
- logical values
- collections
- objects
- functions

---

# Summary

Variables allow programs to store, retrieve, and modify information.

They are one of the fundamental concepts of programming because almost every operation performed by a computer depends on storing data temporarily in memory.

Understanding variables is the first step toward writing useful programs.

---

# Key Takeaways

- Programs work by processing information.
- Variables provide names for values stored in memory.
- Variables make software flexible and reusable.
- Almost every application relies on variables.
- Mastering variables is essential before learning control flow, functions, and objects.

---

## Next Lesson

In the next lesson, you will learn how to create variables in Python, how assignment works, and how to choose meaningful variable names following Python best practices.
