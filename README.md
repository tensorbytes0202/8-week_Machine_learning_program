# 📁 Phase 1 & 2: Python, Data Handling & Statistics (Day 1–10)

Building the foundation for Machine Learning, Data Science, and Artificial Neural Networks.

---

# 🐍 PHASE 1 — PYTHON MASTERY (Day 1–3)

Python is one of the most powerful and beginner-friendly programming languages used in:

- Machine Learning
- Artificial Intelligence
- Data Science
- Web Development
- Automation
- Cybersecurity

The goal of this phase is to build strong programming logic and problem-solving skills.

In real-world Machine Learning jobs, engineers do much more than training models. They also:

- Handle data
- Automate workflows
- Work with files and APIs
- Process datasets
- Build pipelines

This phase builds that foundation.

---

# 📅 Day 1 → Python Basics & Logic

# 📖 Theory

Python is a high-level interpreted programming language known for:

- Simple syntax
- Readability
- Large ecosystem
- Fast development

## 🌍 Real Life Example

If C++ is like driving a manual sports car, Python is like driving an automatic car — easier to learn and faster to use.

---

# 🔹 Variables

Variables are containers used to store data.

## 🌍 Real Life Example

Think of variables like labeled storage boxes:

- One box stores books
- One box stores clothes
- One box stores electronics

Similarly, variables store different kinds of data.

```python
name = "Aditya"
age = 20
marks = 89.5
```

---

# 🔹 Data Types

Every piece of data has a type.

| Data Type | Example | Real-Life Example |
|---|---|---|
| Integer | `10` | Number of students |
| Float | `10.5` | Temperature |
| String | `"Hello"` | User name |
| Boolean | `True` | ON/OFF state |

```python
age = 20
temperature = 36.5
name = "Python"
is_logged_in = True
```

---

# 🔹 Operators

Operators are used to perform calculations.

## 🌍 Real Life Example

A calculator app internally uses mathematical operators.

```python
a = 10
b = 5

print(a + b)
print(a - b)
print(a * b)
print(a / b)
```

---

# 🔹 Input / Output

Input means taking data from the user.

Output means displaying results.

## 🌍 Real Life Example

Instagram login page:

- Username input
- Password input
- Welcome message output

```python
name = input("Enter your name: ")

print("Welcome", name)
```

---

# 🔹 If-Else Conditions

Used for decision-making.

## 🌍 Real Life Example

If bank balance is sufficient → transaction successful  
Else → payment failed

```python
age = 18

if age >= 18:
    print("Eligible to vote")
else:
    print("Not eligible")
```

---

# 🔹 Loops

Loops automate repetitive tasks.

## 🌍 Real Life Example

Instagram continuously loads posts while scrolling. That repeated process is similar to loops.

---

## 🔸 For Loop

Used when the number of iterations is known.

```python
for i in range(5):
    print(i)
```

---

## 🔸 While Loop

Used when execution depends on a condition.

## 🌍 Real Life Example

A game continues running while the player is alive.

```python
count = 0

while count < 5:
    print(count)
    count += 1
```

---

# 🛠 Practice Programs

---

# 🔹 Calculator Program

## 🌍 Real Life Example

Basic logic behind mobile calculator apps.

```python
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

print("Addition:", a + b)
print("Subtraction:", a - b)
print("Multiplication:", a * b)
print("Division:", a / b)
```

---

# 🔹 Prime Number Checker

Prime numbers are heavily used in:

- Cryptography
- Cybersecurity
- Encryption algorithms

```python
num = int(input("Enter a number: "))

if num > 1:
    for i in range(2, int(num**0.5) + 1):
        if num % i == 0:
            print("Not Prime")
            break
    else:
        print("Prime")
else:
    print("Not Prime")
```

---

# 🔹 Fibonacci Series

Fibonacci patterns appear in:

- Nature
- Flowers
- Pineapples
- Trading algorithms
- Optimization problems

```python
n = int(input("Enter number of terms: "))

a, b = 0, 1

for i in range(n):
    print(a)
    a, b = b, a + b
```

---

# 📅 Day 2 → Functions + Data Structures

# 📖 Theory

In large applications, writing the same code repeatedly is inefficient.

Functions help create reusable logic.

Data Structures help organize and manage data efficiently.

## 🌍 Real Life Example

In food delivery apps like Zomato:

- User data
- Restaurant data
- Orders
- Reviews

All are stored using different data structures.

---

# 🔹 Functions

Functions are reusable blocks of code.

## 🌍 Real Life Example

ATM machines use reusable operations like:

- Withdraw money
- Check balance
- Deposit cash

Each operation behaves like a function.

```python
def greet(name):
    return f"Hello {name}"

print(greet("Aditya"))
```

---

# 🔹 Lambda Functions

Lambda functions are small one-line anonymous functions.

Mostly used for quick operations.

```python
square = lambda x: x * x

print(square(5))
```

---

# 🔹 Lists

Lists store multiple items in order.

## 🌍 Real Life Example

A shopping cart stores multiple products.

```python
numbers = [1, 2, 3, 4]

numbers.append(5)

print(numbers)
```

---

# 🔹 Tuples

Tuples are immutable collections.

Once created, they cannot be modified.

## 🌍 Real Life Example

GPS coordinates remain fixed.

```python
coordinates = (28.6139, 77.2090)

print(coordinates)
```

---

# 🔹 Sets

Sets store only unique values.

## 🌍 Real Life Example

Unique student IDs in a college database.

```python
nums = {1, 2, 2, 3, 4}

print(nums)
```

---

# 🔹 Dictionaries

Dictionaries store data in key-value pairs.

## 🌍 Real Life Example

Student record systems:

- Name → Aditya
- Roll Number → 101

```python
student = {
    "name": "Aditya",
    "age": 20
}

print(student["name"])
```

---

# ⭐ List Comprehension (Very Important)

Used for writing compact and optimized loops.

```python
squares = [x*x for x in range(10)]

print(squares)
```

---

# ⭐ Dictionary Handling

```python
student = {
    "name": "Aditya",
    "course": "ML"
}

for key, value in student.items():
    print(key, value)
```

---

# 🛠 Practice Project → Student Management System

## 🌍 Real Life Example

Basic version of a school database system.

```python
students = {}

while True:
    name = input("Enter student name: ")
    marks = int(input("Enter marks: "))

    students[name] = marks

    choice = input("Add more? (y/n): ")

    if choice == 'n':
        break

print(students)
```
