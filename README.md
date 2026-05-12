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


# 📅 Day 3 → OOP + File Handling

# 📖 Theory

Object-Oriented Programming (OOP) is used to model real-world entities into code using:

- Classes
- Objects
- Methods
- Inheritance

Large-scale applications like:

- Instagram
- Uber
- Zomato
- Amazon

all internally use OOP concepts.

---

## 🌍 Real Life Example

A car can be represented as:

- Color
- Brand
- Speed

These properties become attributes inside a class.

---

# 🔹 Classes & Objects

A class is a blueprint.

An object is a real instance of that blueprint.

```python
class Student:

    def __init__(self, name, age):
        self.name = name
        self.age = age

    def display(self):
        print(self.name, self.age)

s1 = Student("Aditya", 20)

s1.display()
```

---

# 🔹 Inheritance

Inheritance allows one class to acquire properties of another class.

## 🌍 Real Life Example

A Dog is an Animal.  
So Dog can inherit properties from Animal.

```python
class Animal:
    def sound(self):
        print("Animal Sound")

class Dog(Animal):
    def bark(self):
        print("Dog Barks")

d = Dog()

d.sound()
d.bark()
```

---

# 🔹 Exception Handling

Used to handle runtime errors gracefully.

## 🌍 Real Life Example

Banking apps should not crash if users enter invalid inputs.

```python
try:
    a = 10 / 0
except ZeroDivisionError:
    print("Cannot divide by zero")
```

---

# 🔹 File Handling

Used for reading and writing files.

## 🌍 Real Life Example

Chat applications save messages in databases/files.

```python
file = open("demo.txt", "w")

file.write("Hello Machine Learning")

file.close()
```

---

# 🔹 pip & Virtual Environment

## 🔸 pip

Used to install Python libraries.

```bash
pip install numpy
```

---

## 🔸 Virtual Environment

Used to isolate project dependencies.

## 🌍 Real Life Example

Different projects may require different library versions.

```bash
python -m venv myenv
```

---

# 🔹 Important Libraries

---

# 🔸 os Library

Used for interacting with the operating system.

```python
import os

print(os.getcwd())
```

---

# 🔸 json Library

Used for JSON data handling.

## 🌍 Real Life Example

APIs mostly exchange data in JSON format.

```python
import json

data = {
    "name": "Aditya"
}

print(json.dumps(data))
```

---

# 🔸 csv Library

Used for CSV file operations.

## 🌍 Real Life Example

Excel datasets are commonly stored as CSV files.

```python
import csv
```

---

# 📊 PHASE 2 — NUMPY + PANDAS + VISUALIZATION (Day 4–10)

NumPy and Pandas are the backbone of Data Science and Machine Learning.

Almost every ML project uses these libraries.

---

# 📅 Day 4–5 → NumPy

# 📖 Theory

NumPy is used for:

- Numerical Computing
- Matrix Operations
- Fast Mathematical Calculations

Artificial Neural Networks internally work with matrices and tensors.

---

## 🌍 Real Life Example

Images in Computer Vision are stored as matrices of pixels.

---

# 🔹 Creating Arrays

```python
import numpy as np

arr = np.array([1, 2, 3])

print(arr)
```

---

# 🔹 Indexing & Slicing

Used for accessing specific elements.

```python
arr = np.array([10, 20, 30, 40])

print(arr[1:3])
```

---

# 🔹 Reshaping Arrays

Changes dimensions of arrays.

```python
arr = np.array([1,2,3,4,5,6])

print(arr.reshape(2,3))
```

---

# 🔹 Broadcasting

Allows mathematical operations on arrays efficiently.

```python
arr = np.array([1,2,3])

print(arr + 5)
```

---

# 🔹 Vectorization

Removes the need for loops and increases speed.

## 🌍 Real Life Example

ML models process millions of values simultaneously.

```python
arr = np.array([1,2,3])

print(arr * 2)
```

---

# 🔹 Matrix Multiplication

Used heavily in:

- Deep Learning
- Computer Graphics
- Neural Networks

## 📌 Formula

```text
C = A × B
```

```python
A = np.array([[1,2],[3,4]])
B = np.array([[5,6],[7,8]])

print(np.dot(A, B))
```

---

# 🛠 Practice Projects

---

# 🔹 Matrix Calculator

```python
import numpy as np

A = np.array([[1,2],[3,4]])
B = np.array([[5,6],[7,8]])

print(A + B)
print(A - B)
print(np.dot(A, B))
```

---

# 🔹 Statistical Operations

```python
arr = np.array([1,2,3,4,5])

print(np.mean(arr))
print(np.std(arr))
```

# 📅 Day 6–7 → Pandas

# 📖 Theory

Pandas is used for:

- Data Analysis
- Data Cleaning
- Data Manipulation

Almost every real-world dataset is processed using Pandas.

---

## 🌍 Real Life Example

Netflix recommendation systems analyze huge tables of user activity.

---

# 🔹 DataFrames

DataFrames are table-like structures.

## 🌍 Real Life Example

Excel sheets are similar to DataFrames.

```python
import pandas as pd

data = {
    "Name": ["A", "B"],
    "Marks": [90, 85]
}

df = pd.DataFrame(data)

print(df)
```

---

# 🔹 CSV Loading

```python
df = pd.read_csv("data.csv")
```

---

# 🔹 Missing Values

Real-world datasets often contain incomplete data.

```python
print(df.isnull().sum())
```

---

# 🔹 Filtering Data

```python
print(df[df["Marks"] > 80])
```

---

# 🔹 GroupBy

Used for grouping similar data.

## 🌍 Real Life Example

E-commerce companies group products by category.

```python
print(df.groupby("Department").mean())
```

---

# 🔹 Data Cleaning

Cleaning bad or incomplete data.

## 🌍 Real Life Example

Removing duplicate users from a database.

```python
df.dropna(inplace=True)
```

---

# 🛠 Projects

---

# 🔹 Netflix Dataset Analysis

```python
import pandas as pd

df = pd.read_csv("netflix.csv")

print(df.head())
print(df.info())
```

---

# 🔹 IPL Dataset Analysis

```python
df = pd.read_csv("ipl.csv")

print(df["team"].value_counts())
```

---

# 📅 Day 8 → Data Visualization

# 📖 Theory

Visualization helps understand data patterns visually.

Machine Learning engineers use visualization to:

- Detect trends
- Find outliers
- Analyze distributions

---

## 🌍 Real Life Example

Stock market graphs and analytics dashboards use visualization.

---

# 🔹 Libraries

- Matplotlib
- Seaborn

---

# 🔹 Histogram

Shows frequency distribution.

```python
import matplotlib.pyplot as plt

data = [1,2,2,3,3,3,4]

plt.hist(data)

plt.show()
```

---

# 🔹 Bar Plot

Used for categorical comparisons.

## 🌍 Real Life Example

Comparing sales of products.

```python
x = ["A", "B", "C"]
y = [10, 20, 30]

plt.bar(x, y)

plt.show()
```

---

# 🔹 Heatmap

Used to visualize correlations.

```python
import seaborn as sns
import numpy as np

data = np.random.rand(5,5)

sns.heatmap(data)
```

---

# 🔹 Pairplot

Shows relationships between features.

```python
sns.pairplot(df)
```

---

# 📅 Day 9–10 → Statistics for Machine Learning

# 📖 Theory

Statistics is the backbone of Machine Learning.

ML models learn patterns from statistical relationships inside data.

Without statistics:

- Model evaluation becomes impossible
- Data understanding becomes weak
- Feature engineering becomes difficult

---

# 🔹 Mean

Average value of data.

## 🌍 Real Life Example

Average marks of students.

## 📌 Formula

```text
μ = Σx / N
```

```python
import numpy as np

arr = [1,2,3,4,5]

print(np.mean(arr))
```

---

# 🔹 Variance

Measures spread of data.

## 🌍 Real Life Example

Difference in student performance levels.

## 📌 Formula

```text
σ² = Σ(x − μ)² / N
```

```python
print(np.var(arr))
```

---

# 🔹 Standard Deviation

Measures how far values are from the mean.

```python
print(np.std(arr))
```

---

# 🔹 Correlation

Shows relationship between variables.

## 🌍 Real Life Example

Study hours vs exam marks.

```python
print(df.corr())
```

---

# 🔹 Probability Basics

Probability measures chances of an event occurring.

## 🌍 Real Life Example

Weather prediction systems use probability.

```python
probability = favorable_cases / total_cases
```

---

# 🔹 Standardization (Z-Score)

Used to scale data before ML training.

## 🌍 Real Life Example

Different exam scoring systems converted to a common scale.

## 📌 Formula

```text
z = (x − μ) / σ
```

```python
from sklearn.preprocessing import StandardScaler
import numpy as np

data = np.array([[10], [20], [30]])

scaler = StandardScaler()

print(scaler.fit_transform(data))
```

# 🤖 PHASE 3 — COMPLETE MACHINE LEARNING (Day 11–15)

Building the core foundation of Machine Learning.

In this phase, students will move from programming and data handling to real Machine Learning concepts.

This phase focuses on:

- Understanding how ML models work
- Preparing real-world datasets
- Training models
- Evaluating predictions
- Understanding regression algorithms

---

# 📅 Day 11 → Introduction to Machine Learning

# 📖 Theory

Machine Learning is a subset of Artificial Intelligence where systems learn patterns from data instead of being explicitly programmed.

Traditional programming follows:

```text
Input + Rules → Output
```

Machine Learning follows:

```text
Input + Output Data → Machine Learns Rules
```

---

# 🌍 Real Life Examples

- Netflix recommends movies using ML.
- YouTube suggests videos based on watch history.
- Gmail detects spam emails.
- Google Maps predicts traffic.
- Amazon recommends products.

---

# 🔹 Types of Machine Learning

---

# 🔸 Supervised Learning

The model learns using labeled data.

## 🌍 Real Life Example

Teaching a child using question-answer pairs.

### Examples

- House Price Prediction
- Spam Detection
- Disease Prediction

```text
Input → Correct Output Available
```

---

# 🔸 Unsupervised Learning

The model learns patterns without labels.

## 🌍 Real Life Example

Grouping similar customers in a shopping mall.

### Examples

- Customer Segmentation
- Clustering
- Pattern Detection

```text
Input → No Correct Output
```

---

# 🔸 Reinforcement Learning

The model learns using rewards and penalties.

## 🌍 Real Life Example

A game AI improving after winning or losing.

### Examples

- Self-driving cars
- Robotics
- Chess AI

---

# 🔹 Machine Learning Workflow

Every ML project follows a pipeline.

```text
Data Collection
        ↓
Data Cleaning
        ↓
Feature Engineering
        ↓
Model Training
        ↓
Evaluation
        ↓
Deployment
```

---

# 🔹 Data Collection

Collecting data from:

- CSV files
- APIs
- Databases
- Sensors
- Websites

## 🌍 Real Life Example

Food delivery apps collect:

- User orders
- Ratings
- Delivery times

---

# 🔹 Data Cleaning

Fixing:

- Missing values
- Duplicate records
- Wrong formats
- Noisy data

## 🌍 Real Life Example

Removing fake or duplicate users from a database.

---

# 🔹 Feature Engineering

Creating useful input features for models.

## 🌍 Real Life Example

Converting date of birth into age.

---

# 🔹 Model Training

The model learns patterns from training data.

```python
from sklearn.linear_model import LinearRegression

model = LinearRegression()
```

---

# 🔹 Model Evaluation

Checking model performance.

### Examples

- Accuracy
- Precision
- Recall
- RMSE

---

# 🔹 Deployment Basics

Deploying ML models into real applications.

## 🌍 Real Life Example

A trained recommendation model deployed inside Netflix.

---

# 📅 Day 12 → Data Preprocessing

# 📖 Theory

Real-world datasets are rarely clean.

Machine Learning models require properly formatted and scaled data.

Data preprocessing improves:

- Accuracy
- Model performance
- Training stability

---

# 🔹 Why Preprocessing is Important

Raw datasets may contain:

- Missing values
- Categorical text
- Different scales
- Outliers
- Noise

Without preprocessing, models perform poorly.

---

# 🔹 Handling Missing Values

Used to fill or remove missing data.

## 🌍 Real Life Example

A customer form missing phone number data.

```python
import pandas as pd

df.fillna(df.mean(), inplace=True)
```

---

# 🔹 Encoding Categorical Data

ML models work with numbers, not text.

Encoding converts labels into numerical values.

## 🌍 Real Life Example

```text
Male   → 0
Female → 1
```

```python
from sklearn.preprocessing import LabelEncoder

le = LabelEncoder()

df['Gender'] = le.fit_transform(df['Gender'])
```

---

# 🔹 Train-Test Split

Splitting dataset into:

- Training data
- Testing data

## 🌍 Real Life Example

Students practice using sample questions before final exams.

```python
from sklearn.model_selection import train_test_split

X_train, X_test, y_train, y_test = train_test_split(
    X, y, test_size=0.2
)
```

---

# 🔹 Feature Scaling

Used when features have different ranges.

## 🌍 Real Life Example

Salary values may be in lakhs while age values are small.

Without scaling, larger values dominate learning.

---

# 🔸 Normalization

Converts values between 0 and 1.

## 📌 Formula

```text
x' = (x - xmin) / (xmax - xmin)
```

```python
from sklearn.preprocessing import MinMaxScaler

scaler = MinMaxScaler()

scaled_data = scaler.fit_transform(data)
```

---

# 🔸 Standardization

Centers data around mean.

## 📌 Formula

```text
z = (x - μ) / σ
```

```python
from sklearn.preprocessing import StandardScaler

scaler = StandardScaler()

scaled = scaler.fit_transform(data)
```

---

# 📅 Day 13 → Linear Regression

# 📖 Theory

Linear Regression predicts continuous numerical values.

It finds the best-fit straight line between input and output.

---

# 🌍 Real Life Examples

- House Price Prediction
- Salary Prediction
- Sales Forecasting
- Temperature Prediction

---

# 🔹 Linear Regression Equation

## 📌 Formula

```text
y = mx + b
```

Where:

- y → predicted output
- m → slope
- x → input feature
- b → intercept

---

# 🔹 Real Life Example

Higher experience generally leads to higher salary.

```text
Experience ↑ → Salary ↑
```

---

# 🔹 Implementing Linear Regression

```python
from sklearn.linear_model import LinearRegression

model = LinearRegression()

model.fit(X_train, y_train)

predictions = model.predict(X_test)
```

---

# 🔹 Visualization

```python
import matplotlib.pyplot as plt

plt.scatter(X, y)
plt.plot(X, model.predict(X))
plt.show()
```

---

# 🔹 Cost Function

The model minimizes prediction error.

## 🌍 Real Life Example

Trying to reduce mistakes in exam score predictions.

---

# 📅 Day 14 → Multiple & Polynomial Regression

# 📖 Theory

Some problems require multiple features.

### Example

House price depends on:

- Area
- Bedrooms
- Location
- Age of house

This is Multiple Linear Regression.

---

# 🔹 Multiple Linear Regression

Uses multiple input variables.

## 📌 Formula

```text
y = b0 + b1x1 + b2x2 + b3x3
```

---

# 🔹 Real Life Example

Predicting car prices using:

- Brand
- Mileage
- Engine power
- Model year

---

# 🔹 Implementation

```python
from sklearn.linear_model import LinearRegression

model = LinearRegression()

model.fit(X_train, y_train)
```

---

# 🔹 Polynomial Regression

Used when relationships are curved instead of linear.

## 🌍 Real Life Example

Student performance may increase rapidly after consistent practice.

---

# 🔹 Polynomial Equation

## 📌 Formula

```text
y = a + bx + cx²
```

---

# 🔹 Polynomial Features

```python
from sklearn.preprocessing import PolynomialFeatures

poly = PolynomialFeatures(degree=2)

X_poly = poly.fit_transform(X)
```

---

# 📅 Day 15 → Gradient Descent

# 📖 Theory

Gradient Descent is one of the most important optimization algorithms in Machine Learning and Deep Learning.

It helps models learn by reducing error step-by-step.

---

# 🌍 Real Life Example

Imagine standing on a mountain blindfolded and trying to reach the lowest point.

You take small steps downward until you reach the bottom.

That process is similar to Gradient Descent.

---

# 🔹 Goal of Gradient Descent

Minimize the loss function.

The model continuously updates weights to reduce prediction error.

---

# 🔹 Gradient Descent Formula

## 📌 Formula

```text
θ = θ - α * ∂J/∂θ
```

Where:

- θ → parameters/weights
- α → learning rate
- J → cost function

---

# 🔹 Learning Rate

Controls step size during optimization.

---

## 🔸 Small Learning Rate

- Slow learning
- Stable training

---

## 🔸 Large Learning Rate

- Fast learning
- Risk of overshooting

---

# 🔹 Cost Function

Measures model error.

## 🌍 Real Life Example

Difference between actual exam marks and predicted marks.

---

# 🔹 Simple Gradient Descent Example

```python
learning_rate = 0.01
weight = 5
gradient = 2

weight = weight - learning_rate * gradient

print(weight)
```

---

# 🔹 Why Gradient Descent Matters

Used in:

- Linear Regression
- Logistic Regression
- Neural Networks
- Deep Learning
- TensorFlow
- PyTorch

Without Gradient Descent, modern AI systems cannot train efficiently.
