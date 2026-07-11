 # 📘 Lecture 03: Variables and Data Types  

Variables are used to store data, while data types define the kind of information stored inside a variable.

Understanding variables and data types is one of the most important foundations of programming because every program works with data.

---

# Variables and Data Types Concepts

- What is a Variable
- What is Memory
- Assignment Operator
- Variable Naming Rules
- Reserved Keywords in Python
- Data Types in Python
- String Data Type
- Integer Data Type
- Float Data Type
- Boolean Data Type
- `type()` Function

---

# What is a Variable?

## Definition

A variable is a name given to a memory location where data is stored.

### Simple Definition

A variable is like a container that holds data.

## Example

```python
name = "Zoha"
```

Here:

- `name` = Variable
- `"Zoha"` = Stored Value

---

# What is Memory?

## Definition

Memory (RAM) is the computer’s temporary storage area.

### Simple Definition

Memory is a place where data is stored while a program is running.

## Easy Example

Think of memory like a:

🧠 **Whiteboard in a classroom**

- You write information temporarily.
- When erased → data is gone.

---
# Variable Naming Rules

## Rules

✔ Must start with a letter or underscore (`_`)

✔ Cannot start with a number

✔ No spaces allowed

✔ Case-sensitive

✔ Cannot use reserved keywords

✔ Variable names may contain:
- Uppercase letters (`A-Z`)
- Lowercase letters (`a-z`)
- Numbers (`0-9`)
- Underscore (`_`)# Important Note on Keywords

✔ Keywords are built-in words.

✔ Python uses them for logic and program structure.

✔ We should never use them as variable names.

✔ Keywords already have special meanings in Python.

---

# Data Types in Python

Python has different types of data.

---

# 1️⃣ String (`str`)

Text data.

## Example

```python
name = "Zoha"
```

---

# 2️⃣ Integer (`int`)

Whole numbers.

## Example

```python
age = 20
```

---

# 3️⃣ Float (`float`)

Decimal numbers.

## Example

```python
price = 99.5
```

---

# 4️⃣ Boolean (`bool`)

True / False values.

## Example

```python
is_student = True
```

---

# `type()` Function

We use `type()` to check a variable's data type.

## Example

```python
x = 10
print(type(x))
```

## Output

```python
<class 'int'>
```

## Purpose

Helps us know what type of data a variable stores.

## Code

This is my second Python assignment, introducing the fundamental concepts of Variables and Data Types in Python, including variables, memory, naming rules, data types, and the `type()` function.


```python
name = "Mariam Kamran"
age = 12
city = "Karachi"
course = "JavaScript and Python"

print("My name is", name)
print(type(name))

print("I am", age, "years old")
print(type(age))

print("I live in", city)
print(type(city))

print("I am currently learning", course)
print(type(course))
```

## Output

```
My name is Mariam Kamran
<class 'str'>

I am 12 years old
<class 'int'>

I live in Karachi
<class 'str'>

I am currently learning JavaScript and Python
<class 'str'>
```
