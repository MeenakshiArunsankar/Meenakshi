# Python Conditionals: A Beginner's Guide  

Conditionals in Python allow you to execute certain blocks of code based on specific conditions. They are implemented using statements like `if`, `elif`, and `else`.

---

## Table of Contents
1. [What Are Conditionals?](#what-are-conditionals)
2. [The `if` Statement](#the-if-statement)
3. [The `else` Statement](#the-else-statement)
4. [The `elif` Statement](#the-elif-statement)
5. [Nested Conditionals](#nested-conditionals)
6. [Examples](#examples)
7. [Exercises](#exercises)

---

## What Are Conditionals?
Conditionals are decision-making statements that allow you to control the flow of a program. They execute code blocks only when certain conditions are met.  

---

## The `if` Statement  
The `if` statement is used to test a condition. If the condition evaluates to `True`, the block of code inside the `if` statement is executed.  

**Syntax:**  
```python
if condition:
    # Code to execute if the condition is True
```

**Example:**  
```python
age = 18
if age >= 18:
    print("You are eligible to vote.")
```

---

## The `else` Statement  
The `else` statement provides an alternative block of code that executes when the `if` condition is `False`.  

**Syntax:**  
```python
if condition:
    # Code if condition is True
else:
    # Code if condition is False
```

**Example:**  
```python
age = 16
if age >= 18:
    print("You are eligible to vote.")
else:
    print("You are not eligible to vote.")
```

---

## The `elif` Statement  
The `elif` statement allows you to check multiple conditions. It stands for "else if."  

**Syntax:**  
```python
if condition1:
    # Code if condition1 is True
elif condition2:
    # Code if condition2 is True
else:
    # Code if none of the above conditions are True
```

**Example:**  
```python
marks = 85
if marks >= 90:
    print("Grade: A")
elif marks >= 75:
    print("Grade: B")
else:
    print("Grade: C")
```

---

## Nested Conditionals  
You can use conditionals inside other conditionals. This is known as nesting.  

**Example:**  
```python
num = 10
if num > 0:
    if num % 2 == 0:
        print("Positive Even Number")
    else:
        print("Positive Odd Number")
else:
    print("Negative Number or Zero")
```

---

## Examples  

### Example 1: Checking Even or Odd  
```python
number = 7
if number % 2 == 0:
    print("Even")
else:
    print("Odd")
```

### Example 2: Finding the Largest Number  
```python
a, b, c = 5, 10, 3
if a > b and a > c:
    print("a is the largest")
elif b > c:
    print("b is the largest")
else:
    print("c is the largest")
```

---

## Exercises  

### Exercise 1: Voter Eligibility  
Write a program to check if a person is eligible to vote.  
- Input: `age = 17`  
- Output: `You are not eligible to vote.`  

### Exercise 2: Grading System  
Create a program that assigns grades based on marks:  
- Marks >= 90: `A`  
- Marks >= 75: `B`  
- Marks < 75: `C`  

---

## Summary  
- Use `if` to check conditions.  
- Use `else` to provide alternatives.  
- Use `elif` for multiple conditions.  
- Nest conditionals for complex logic.  

---

Happy Coding! 🎉  
