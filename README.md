# 🐍 Python Mastery — Beginner to Advanced

> A practical, GitHub-ready Python learning repository covering Python fundamentals through advanced and professional development concepts, with runnable examples, exercises, projects, and interview preparation.

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Level](https://img.shields.io/badge/Level-Beginner%20%E2%86%92%20Advanced-orange)
![Examples](https://img.shields.io/badge/Examples-100%2B-purple)

---

## 📖 About This Repository

This repository is designed as a **complete Python learning path** rather than just a syntax reference.

You will progress through:

```text
Python Basics
    ↓
Data Structures
    ↓
Control Flow
    ↓
Functions
    ↓
Modules & Packages
    ↓
Object-Oriented Programming
    ↓
Exceptions & Files
    ↓
Iterators / Generators / Decorators
    ↓
Testing / Logging / Type Hints
    ↓
APIs / Databases
    ↓
Concurrency / Asyncio
    ↓
Advanced Python
    ↓
Production Python
```

The examples are intentionally small so you can copy, run, modify, and experiment with them.

---

# 📚 Table of Contents

- [Prerequisites](#-prerequisites)
- [Installation](#-installation)
- [Quick Start](#-quick-start)
- [Repository Structure](#-repository-structure)
- [Learning Roadmap](#-learning-roadmap)
- [01 — Python Basics](#01--python-basics)
- [02 — Variables and Data Types](#02--variables-and-data-types)
- [03 — Strings](#03--strings)
- [04 — Collections](#04--collections)
- [05 — Operators](#05--operators)
- [06 — Conditional Statements](#06--conditional-statements)
- [07 — Loops](#07--loops)
- [08 — Functions](#08--functions)
- [09 — Comprehensions](#09--comprehensions)
- [10 — Modules and Packages](#10--modules-and-packages)
- [11 — Exception Handling](#11--exception-handling)
- [12 — File Handling](#12--file-handling)
- [13 — Object-Oriented Programming](#13--object-oriented-programming)
- [14 — Iterators and Generators](#14--iterators-and-generators)
- [15 — Decorators](#15--decorators)
- [16 — Context Managers](#16--context-managers)
- [17 — Regular Expressions](#17--regular-expressions)
- [18 — Type Hints](#18--type-hints)
- [19 — Dataclasses and Enums](#19--dataclasses-and-enums)
- [20 — JSON and APIs](#20--json-and-apis)
- [21 — Databases](#21--databases)
- [22 — Testing](#22--testing)
- [23 — Logging](#23--logging)
- [24 — Debugging](#24--debugging)
- [25 — Functional Programming](#25--functional-programming)
- [26 — Concurrency](#26--concurrency)
- [27 — Asyncio](#27--asyncio)
- [28 — Memory and Performance](#28--memory-and-performance)
- [29 — Advanced Python](#29--advanced-python)
- [30 — Professional Python](#30--professional-python)
- [100+ Example Ideas](#-100-example-ideas)
- [Exercises](#-exercises)
- [Projects](#-projects)
- [Interview Questions](#-interview-questions)
- [Best Practices](#-best-practices)
- [Contributing](#-contributing)
- [License](#-license)

---

# 🧰 Prerequisites

You do not need prior Python experience.

Recommended:

- Basic computer knowledge
- A code editor such as VS Code, PyCharm, or another editor
- Terminal/command-line familiarity
- Curiosity and willingness to experiment

---

# 💻 Installation

## Check Python

```bash
python --version
```

On some systems:

```bash
python3 --version
```

You should use a currently supported Python release.

## Create a virtual environment

Linux/macOS:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

Windows:

```powershell
py -m venv .venv
.venv\Scripts\activate
```

Upgrade pip:

```bash
python -m pip install --upgrade pip
```

---

# 🚀 Quick Start

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/python-mastery.git
cd python-mastery
```

Run an example:

```bash
python examples/01_basics/hello.py
```

Run tests:

```bash
pytest
```

---

# 📁 Repository Structure

A recommended structure for this repository:

```text
python-mastery/
│
├── README.md
├── LICENSE
├── .gitignore
├── pyproject.toml
│
├── examples/
│   ├── 01_basics/
│   ├── 02_variables/
│   ├── 03_strings/
│   ├── 04_collections/
│   ├── 05_operators/
│   ├── 06_conditions/
│   ├── 07_loops/
│   ├── 08_functions/
│   ├── 09_comprehensions/
│   ├── 10_modules/
│   ├── 11_exceptions/
│   ├── 12_files/
│   ├── 13_oop/
│   ├── 14_iterators_generators/
│   ├── 15_decorators/
│   ├── 16_context_managers/
│   ├── 17_regex/
│   ├── 18_type_hints/
│   ├── 19_dataclasses/
│   ├── 20_json_api/
│   ├── 21_database/
│   ├── 22_testing/
│   ├── 23_logging/
│   ├── 24_debugging/
│   ├── 25_functional/
│   ├── 26_concurrency/
│   ├── 27_asyncio/
│   └── 28_advanced/
│
├── exercises/
│   ├── beginner/
│   ├── intermediate/
│   └── advanced/
│
├── projects/
│   ├── calculator/
│   ├── todo_cli/
│   ├── expense_tracker/
│   ├── contact_manager/
│   ├── sqlite_crud/
│   └── api_client/
│
└── tests/
```

---

# 🗺️ Learning Roadmap

| Stage | Topics | Goal |
|---|---|---|
| 🟢 Beginner | Syntax, variables, collections, conditions, loops | Write basic programs |
| 🟡 Intermediate | Functions, modules, files, exceptions, OOP | Build applications |
| 🟠 Advanced | Generators, decorators, context managers, typing | Write idiomatic Python |
| 🔴 Professional | Testing, APIs, databases, concurrency, packaging | Build maintainable software |

---

# 01 — Python Basics

## Hello World

```python
print("Hello, World!")
```

## Comments

```python
# Single-line comment

"""
Documentation string.
"""
```

## Multiple print arguments

```python
name = "Alice"
age = 25

print(name, age)
```

### Exercise

Write a program that prints:

```text
Name: Alice
Age: 25
City: Delhi
```

---

# 02 — Variables and Data Types

Python variables are names bound to objects.

```python
name = "Alice"
age = 25
price = 99.99
active = True
nothing = None
```

Check a type:

```python
print(type(age))
```

## Multiple assignment

```python
x, y, z = 10, 20, 30
```

## Type conversion

```python
age = int("25")
price = float("10.5")
number = str(100)
```

## Boolean conversion

```python
print(bool(0))       # False
print(bool(1))       # True
print(bool(""))      # False
print(bool("hello")) # True
```

### Exercise

Create variables for:

- Name
- Age
- Height
- Is student
- Country

Print their values and types.

---

# 03 — Strings

```python
message = "Python is awesome"
```

## Indexing

```python
text = "Python"

print(text[0])
print(text[-1])
```

## Slicing

```python
print(text[0:3])
print(text[:3])
print(text[3:])
print(text[::-1])
```

## Methods

```python
text = "hello python"

print(text.upper())
print(text.lower())
print(text.title())
print(text.replace("python", "world"))
print(text.split())
```

## f-strings

```python
name = "Alice"
age = 25

print(f"{name} is {age} years old.")
```

## String formatting

```python
price = 1234.5678

print(f"${price:.2f}")
```

### Exercise

Ask the user for first name and last name and print a formatted full name.

---

# 04 — Collections

## List

```python
numbers = [1, 2, 3]

numbers.append(4)
numbers.remove(2)

print(numbers)
```

## Tuple

```python
coordinates = (10, 20)
```

Tuples are immutable.

## Set

```python
numbers = {1, 2, 2, 3}

print(numbers)
```

Sets automatically remove duplicates.

## Dictionary

```python
user = {
    "name": "Alice",
    "age": 25
}

print(user["name"])
print(user.get("email"))
```

## Dictionary iteration

```python
for key, value in user.items():
    print(key, value)
```

### Exercise

Create a dictionary representing a product:

```text
name
price
quantity
category
```

Calculate its total price.

---

# 05 — Operators

## Arithmetic

```python
a = 10
b = 3

print(a + b)
print(a - b)
print(a * b)
print(a / b)
print(a // b)
print(a % b)
print(a ** b)
```

## Comparison

```python
print(10 == 10)
print(10 != 5)
print(10 > 5)
print(10 < 20)
```

## Logical

```python
age = 25

print(age >= 18 and age <= 60)
print(age < 18 or age > 60)
print(not age < 18)
```

## Membership

```python
numbers = [1, 2, 3]

print(2 in numbers)
print(10 not in numbers)
```

## Identity

```python
value = None

print(value is None)
```

### Important: `==` vs `is`

```python
a = [1, 2]
b = [1, 2]

print(a == b)  # Values are equal
print(a is b)  # Different objects
```

---

# 06 — Conditional Statements

## if

```python
age = 20

if age >= 18:
    print("Adult")
```

## if / else

```python
if age >= 18:
    print("Adult")
else:
    print("Minor")
```

## elif

```python
marks = 85

if marks >= 90:
    grade = "A"
elif marks >= 75:
    grade = "B"
elif marks >= 60:
    grade = "C"
else:
    grade = "D"

print(grade)
```

## Conditional expression

```python
status = "Adult" if age >= 18 else "Minor"
```

### Exercise

Build a grade calculator.

---

# 07 — Loops

## for

```python
for number in range(5):
    print(number)
```

## while

```python
count = 0

while count < 5:
    print(count)
    count += 1
```

## break

```python
for number in range(10):
    if number == 5:
        break
    print(number)
```

## continue

```python
for number in range(10):
    if number % 2 == 0:
        continue

    print(number)
```

## enumerate

```python
names = ["Alice", "Bob", "Charlie"]

for index, name in enumerate(names):
    print(index, name)
```

## zip

```python
names = ["Alice", "Bob"]
ages = [25, 30]

for name, age in zip(names, ages):
    print(name, age)
```

### Exercise

Print the multiplication table for a number entered by the user.

---

# 08 — Functions

```python
def greet():
    print("Hello!")
```

Call:

```python
greet()
```

## Parameters

```python
def greet(name):
    print(f"Hello {name}!")
```

## Return

```python
def add(a, b):
    return a + b

result = add(10, 20)
```

## Default arguments

```python
def greet(name="Guest"):
    print(f"Hello {name}")
```

## Keyword arguments

```python
def user_info(name, age):
    print(name, age)

user_info(age=25, name="Alice")
```

## `*args`

```python
def total(*numbers):
    return sum(numbers)

print(total(1, 2, 3, 4))
```

## `**kwargs`

```python
def show_info(**data):
    for key, value in data.items():
        print(key, value)

show_info(name="Alice", age=25)
```

### Important: mutable default arguments

Avoid:

```python
def add_item(item, items=[]):
    items.append(item)
    return items
```

Prefer:

```python
def add_item(item, items=None):
    if items is None:
        items = []

    items.append(item)
    return items
```

---

# 09 — Comprehensions

## List comprehension

```python
squares = [x * x for x in range(10)]
```

## With condition

```python
even_numbers = [
    x for x in range(20)
    if x % 2 == 0
]
```

## Dictionary comprehension

```python
squares = {
    x: x * x
    for x in range(5)
}
```

## Set comprehension

```python
remainders = {
    x % 3
    for x in range(10)
}
```

## Generator expression

```python
squares = (x * x for x in range(10))
```

Use comprehensions when they improve clarity; do not force complex logic into a one-liner.

---

# 10 — Modules and Packages

Suppose `math_utils.py` contains:

```python
def add(a, b):
    return a + b
```

Import it:

```python
import math_utils

print(math_utils.add(2, 3))
```

Or:

```python
from math_utils import add

print(add(2, 3))
```

## Standard library

```python
import math
import random
import datetime
import pathlib
import json
```

Example:

```python
import math

print(math.sqrt(25))
```

---

# 11 — Exception Handling

```python
try:
    number = int(input("Number: "))
    result = 10 / number

except ValueError:
    print("Please enter a valid number.")

except ZeroDivisionError:
    print("Cannot divide by zero.")
```

## else

```python
try:
    result = 10 / 2
except ZeroDivisionError:
    print("Error")
else:
    print(result)
```

## finally

```python
try:
    print("Work")
finally:
    print("Cleanup")
```

## Raise

```python
def withdraw(balance, amount):
    if amount > balance:
        raise ValueError("Insufficient balance")

    return balance - amount
```

### Best practice

Catch specific exceptions:

```python
except ValueError:
    ...
```

rather than:

```python
except Exception:
    ...
```

unless broad handling is intentional.

---

# 12 — File Handling

## Read

```python
with open("data.txt", "r", encoding="utf-8") as file:
    content = file.read()

print(content)
```

## Write

```python
with open("data.txt", "w", encoding="utf-8") as file:
    file.write("Hello Python")
```

## Append

```python
with open("data.txt", "a", encoding="utf-8") as file:
    file.write("\nNew line")
```

## `pathlib`

Modern path handling:

```python
from pathlib import Path

path = Path("data.txt")

path.write_text(
    "Hello Python",
    encoding="utf-8"
)

print(path.read_text(encoding="utf-8"))
```

---

# 13 — Object-Oriented Programming

## Class

```python
class Person:

    def __init__(self, name, age):
        self.name = name
        self.age = age

    def introduce(self):
        return f"I am {self.name}."


person = Person("Alice", 25)

print(person.introduce())
```

## Class attributes

```python
class Dog:
    species = "Canis familiaris"

    def __init__(self, name):
        self.name = name
```

## Inheritance

```python
class Animal:

    def speak(self):
        return "Animal sound"


class Dog(Animal):

    def speak(self):
        return "Woof"
```

## `super()`

```python
class Person:

    def __init__(self, name):
        self.name = name


class Employee(Person):

    def __init__(self, name, employee_id):
        super().__init__(name)
        self.employee_id = employee_id
```

## Polymorphism

```python
class Dog:
    def speak(self):
        return "Woof"


class Cat:
    def speak(self):
        return "Meow"


animals = [Dog(), Cat()]

for animal in animals:
    print(animal.speak())
```

## Property

```python
class Account:

    def __init__(self, balance):
        self._balance = balance

    @property
    def balance(self):
        return self._balance

    @balance.setter
    def balance(self, value):
        if value < 0:
            raise ValueError("Balance cannot be negative")

        self._balance = value
```

---

# 14 — Iterators and Generators

## Iterator

```python
numbers = iter([10, 20, 30])

print(next(numbers))
print(next(numbers))
```

## Custom iterator

```python
class Counter:

    def __init__(self, limit):
        self.current = 0
        self.limit = limit

    def __iter__(self):
        return self

    def __next__(self):
        if self.current >= self.limit:
            raise StopIteration

        self.current += 1
        return self.current
```

## Generator

```python
def countdown(n):
    while n > 0:
        yield n
        n -= 1


for number in countdown(5):
    print(number)
```

Generators are useful for lazy processing and large data streams.

---

# 15 — Decorators

A decorator wraps another function.

```python
from functools import wraps


def logger(func):

    @wraps(func)
    def wrapper(*args, **kwargs):
        print(f"Calling {func.__name__}")
        return func(*args, **kwargs)

    return wrapper


@logger
def greet(name):
    return f"Hello {name}"


print(greet("Alice"))
```

## Decorator with arguments

```python
from functools import wraps


def repeat(times):

    def decorator(func):

        @wraps(func)
        def wrapper(*args, **kwargs):
            result = None

            for _ in range(times):
                result = func(*args, **kwargs)

            return result

        return wrapper

    return decorator
```

---

# 16 — Context Managers

Built-in example:

```python
with open("data.txt", encoding="utf-8") as file:
    data = file.read()
```

Custom context manager:

```python
class Resource:

    def __enter__(self):
        print("Resource acquired")
        return self

    def __exit__(self, exc_type, exc_value, traceback):
        print("Resource released")


with Resource():
    print("Using resource")
```

---

# 17 — Regular Expressions

```python
import re

text = "Order ID: 12345"

match = re.search(r"\d+", text)

if match:
    print(match.group())
```

Useful patterns:

```text
\d   digit
\w   word character
\s   whitespace
+    one or more
*    zero or more
?    optional
^    beginning
$    end
```

Example:

```python
pattern = r"^[\w.-]+@[\w.-]+\.\w+$"

email = "user@example.com"

if re.match(pattern, email):
    print("Valid email format")
```

For security-sensitive validation, prefer dedicated parsers/validators where appropriate rather than relying solely on a regex.

---

# 18 — Type Hints

```python
def add(a: int, b: int) -> int:
    return a + b
```

## Collections

```python
def total(numbers: list[int]) -> int:
    return sum(numbers)
```

## Optional values

Modern Python:

```python
def find_user(user_id: int) -> str | None:
    return None
```

## Type aliases

```python
User = dict[str, str]
```

Type hints improve readability, IDE support, static analysis, and maintainability.

They do not automatically enforce types at runtime.

---

# 19 — Dataclasses and Enums

## Dataclass

```python
from dataclasses import dataclass


@dataclass
class User:
    name: str
    age: int


user = User("Alice", 25)

print(user)
```

## Default value

```python
@dataclass
class Product:
    name: str
    price: float
    quantity: int = 1
```

## Enum

```python
from enum import Enum


class Status(Enum):
    PENDING = "pending"
    APPROVED = "approved"
    REJECTED = "rejected"


print(Status.APPROVED.value)
```

---

# 20 — JSON and APIs

## JSON serialization

```python
import json

user = {
    "name": "Alice",
    "age": 25
}

text = json.dumps(user)

print(text)
```

## JSON parsing

```python
data = '{"name": "Alice", "age": 25}'

user = json.loads(data)

print(user["name"])
```

## HTTP API

Using `requests`:

```python
import requests

response = requests.get(
    "https://api.example.com/users",
    timeout=10
)

response.raise_for_status()

data = response.json()
```

Good API practices:

- Use timeouts.
- Check status codes.
- Handle network failures.
- Validate response data.
- Never hard-code API secrets.
- Keep credentials outside source code.

---

# 21 — Databases

## SQLite

SQLite is included with Python.

```python
import sqlite3

connection = sqlite3.connect("app.db")

cursor = connection.cursor()

cursor.execute("""
    CREATE TABLE IF NOT EXISTS users (
        id INTEGER PRIMARY KEY,
        name TEXT NOT NULL
    )
""")

cursor.execute(
    "INSERT INTO users (name) VALUES (?)",
    ("Alice",)
)

connection.commit()
connection.close()
```

## Parameterized SQL

Good:

```python
cursor.execute(
    "SELECT * FROM users WHERE name = ?",
    (name,)
)
```

Avoid constructing SQL using user-controlled string interpolation.

For production systems, learn the database driver and ORM appropriate to your stack.

---

# 22 — Testing

## unittest

```python
import unittest


def add(a, b):
    return a + b


class TestAdd(unittest.TestCase):

    def test_add(self):
        self.assertEqual(add(2, 3), 5)


if __name__ == "__main__":
    unittest.main()
```

## pytest

```python
def test_add():
    assert add(2, 3) == 5
```

Run:

```bash
pytest
```

## Test edge cases

For a function:

```python
def divide(a, b):
    return a / b
```

Test:

```text
Normal values
Zero
Negative values
Very large values
Invalid inputs
```

---

# 23 — Logging

Prefer structured logging over scattered `print()` statements in applications.

```python
import logging

logging.basicConfig(level=logging.INFO)

logger = logging.getLogger(__name__)

logger.debug("Debug information")
logger.info("Application started")
logger.warning("Warning")
logger.error("Something failed")
```

Levels:

```text
DEBUG
INFO
WARNING
ERROR
CRITICAL
```

---

# 24 — Debugging

Use the built-in debugger:

```python
def calculate(a, b):
    result = a + b

    breakpoint()

    return result
```

Useful techniques:

- Read tracebacks from bottom to top.
- Reproduce the smallest failing case.
- Inspect variable values.
- Use a debugger instead of adding many temporary prints.
- Add regression tests after fixing bugs.

---

# 25 — Functional Programming

## `map`

```python
numbers = [1, 2, 3, 4]

squares = list(
    map(lambda x: x * x, numbers)
)
```

## `filter`

```python
numbers = [1, 2, 3, 4, 5]

even = list(
    filter(lambda x: x % 2 == 0, numbers)
)
```

## `reduce`

```python
from functools import reduce

total = reduce(
    lambda a, b: a + b,
    [1, 2, 3, 4]
)
```

Often, built-ins and comprehensions are clearer:

```python
total = sum([1, 2, 3, 4])
```

---

# 26 — Concurrency

Three major approaches:

```text
Threading
Multiprocessing
Asyncio
```

The correct choice depends on whether the workload is CPU-bound, I/O-bound, and whether the libraries involved support asynchronous execution.

## Thread pool

```python
from concurrent.futures import ThreadPoolExecutor


def square(x):
    return x * x


with ThreadPoolExecutor(max_workers=4) as executor:
    results = list(
        executor.map(square, [1, 2, 3, 4])
    )

print(results)
```

---

# 27 — Asyncio

```python
import asyncio


async def task(name):
    print(f"Starting {name}")
    await asyncio.sleep(1)
    print(f"Finished {name}")


async def main():
    await asyncio.gather(
        task("A"),
        task("B"),
        task("C"),
    )


asyncio.run(main())
```

Asyncio is especially useful for applications with many concurrent I/O operations.

---

# 28 — Memory and Performance

## References

```python
a = [1, 2, 3]
b = a

b.append(4)

print(a)
```

`a` and `b` refer to the same list.

## Copy

```python
a = [1, 2, 3]
b = a.copy()

b.append(4)

print(a)
print(b)
```

## Deep copy

```python
import copy

a = [[1, 2], [3, 4]]
b = copy.deepcopy(a)
```

## Generator for lazy processing

Instead of:

```python
values = [x * x for x in range(1_000_000)]
```

you can process lazily:

```python
values = (x * x for x in range(1_000_000))
```

Measure before optimizing:

```python
import time

start = time.perf_counter()

# Code to measure

elapsed = time.perf_counter() - start

print(elapsed)
```

---

# 29 — Advanced Python

## Closures

```python
def multiplier(n):

    def multiply(x):
        return x * n

    return multiply


double = multiplier(2)

print(double(10))
```

## `nonlocal`

```python
def counter():

    count = 0

    def increment():
        nonlocal count
        count += 1
        return count

    return increment


counter_fn = counter()

print(counter_fn())
print(counter_fn())
```

## Dunder methods

```python
class Person:

    def __init__(self, name):
        self.name = name

    def __str__(self):
        return self.name

    def __repr__(self):
        return f"Person(name={self.name!r})"
```

Common methods:

```text
__init__
__str__
__repr__
__len__
__iter__
__next__
__eq__
__lt__
__add__
__enter__
__exit__
```

## Method Resolution Order

```python
class A:
    pass


class B(A):
    pass


class C(B):
    pass


print(C.mro())
```

## Abstract Base Classes

```python
from abc import ABC, abstractmethod


class Payment(ABC):

    @abstractmethod
    def pay(self, amount):
        pass


class CardPayment(Payment):

    def pay(self, amount):
        print(f"Paid {amount}")
```

## Protocols

Structural typing:

```python
from typing import Protocol


class Speaker(Protocol):

    def speak(self) -> str:
        ...
```

An object can satisfy a protocol based on its behavior rather than requiring explicit inheritance.

---

# 30 — Professional Python

## Recommended tools

| Tool | Purpose |
|---|---|
| `venv` | Virtual environments |
| `pip` | Package installation |
| `pytest` | Testing |
| Ruff | Linting and formatting |
| mypy | Static type checking |
| Git | Version control |
| pre-commit | Automated checks |
| Docker | Containerization |

Choose tools based on project requirements and team conventions.

## Example `pyproject.toml`

```toml
[project]
name = "my-python-project"
version = "0.1.0"
description = "A Python project"
requires-python = ">=3.10"
dependencies = []

[project.optional-dependencies]
dev = [
    "pytest",
    "ruff",
    "mypy",
]
```

## Professional principles

- Keep functions focused.
- Prefer clear names.
- Validate external input.
- Handle errors intentionally.
- Write tests.
- Use type hints where useful.
- Log important application events.
- Keep secrets out of source control.
- Document public interfaces.
- Measure performance before optimizing.
- Keep dependencies current and reviewed.
- Use automated checks in CI.

---

# 💯 100+ Example Ideas

Use these as a progressive practice bank.

## Beginner Examples

1. Hello World
2. Personal introduction
3. Add two numbers
4. Area of a circle
5. Celsius to Fahrenheit
6. Fahrenheit to Celsius
7. Even or odd
8. Positive or negative
9. Largest of two numbers
10. Largest of three numbers
11. Leap year checker
12. Grade calculator
13. Simple calculator
14. BMI calculator
15. Age calculator
16. Multiplication table
17. Countdown
18. Number guessing game
19. Simple quiz
20. Rock-paper-scissors

## Collections

21. Find list maximum
22. Find list minimum
23. Remove duplicates
24. Count list items
25. Reverse a list
26. Sort a list
27. Find common elements
28. Merge dictionaries
29. Word frequency counter
30. Character frequency counter

## Strings

31. Reverse a string
32. Palindrome checker
33. Count vowels
34. Count words
35. Capitalize words
36. Remove whitespace
37. Replace words
38. Extract numbers
39. Email format checker
40. Password strength checker

## Functions

41. Recursive factorial
42. Fibonacci function
43. Prime checker
44. Prime number generator
45. GCD
46. LCM
47. Power function
48. Temperature converter
49. Currency converter
50. Statistics helper

## Files

51. Read text file
52. Write text file
53. Count lines
54. Count words
55. Search text
56. Replace text
57. File extension counter
58. File organizer
59. CSV reader
60. JSON reader

## OOP

61. Person class
62. Bank account
63. Employee management
64. Library management
65. Shopping cart
66. Inventory system
67. Vehicle hierarchy
68. Shape hierarchy
69. School management
70. Hotel management

## Intermediate

71. CLI todo app
72. Expense tracker
73. Contact manager
74. Password generator
75. URL shortener simulation
76. Log analyzer
77. Duplicate file finder
78. Image metadata tool
79. Directory statistics
80. Markdown converter

## APIs / Databases

81. REST API client
82. Weather API client
83. GitHub API client
84. SQLite CRUD
85. User database
86. Product database
87. API pagination example
88. API retry logic
89. API caching
90. Database migration example

## Advanced

91. Custom iterator
92. Generator pipeline
93. Timing decorator
94. Retry decorator
95. Context manager
96. Plugin architecture
97. Async HTTP client
98. Concurrent file processor
99. Task queue simulation
100. Background worker

## Professional Projects

101. REST API service
102. Authentication service
103. Async web crawler
104. CLI framework
105. ETL pipeline
106. Job scheduler
107. Monitoring service
108. Data processing pipeline
109. Microservice
110. Production-ready backend

---

# 📝 Exercises

## Beginner

### Exercise 1 — Even Numbers

Print all even numbers between 1 and 100.

### Exercise 2 — Factorial

Write:

```python
factorial(5)
```

Expected:

```text
120
```

### Exercise 3 — Palindrome

Determine whether:

```text
madam
```

is a palindrome.

### Exercise 4 — Frequency

Input:

```text
python python java python
```

Expected frequency:

```text
python: 3
java: 1
```

---

# 🧩 Intermediate Exercises

### Exercise 5 — Expense Tracker

Implement:

```text
add expense
remove expense
list expenses
calculate total
save to JSON
load from JSON
```

### Exercise 6 — Contact Manager

Implement:

```text
add contact
search contact
update contact
delete contact
list contacts
```

### Exercise 7 — File Organizer

Organize files by extension:

```text
documents/
images/
videos/
archives/
```

---

# 🧠 Advanced Exercises

### Exercise 8 — Retry Decorator

Create:

```python
@retry(times=3)
def unstable_operation():
    ...
```

### Exercise 9 — Custom Context Manager

Create a context manager that measures execution time.

### Exercise 10 — Async Tasks

Create multiple asynchronous tasks and execute them concurrently.

---

# 🏗️ Project Roadmap

## Project 1 — Calculator

Concepts:

```text
Input
Output
Operators
Functions
Exceptions
```

## Project 2 — To-Do CLI

Concepts:

```text
Lists
Dictionaries
Functions
Files
JSON
CLI
```

## Project 3 — Expense Tracker

Concepts:

```text
OOP
JSON
Dataclasses
Exceptions
Testing
```

## Project 4 — SQLite CRUD

Concepts:

```text
SQLite
SQL
Repositories
OOP
Testing
```

## Project 5 — REST API Client

Concepts:

```text
HTTP
JSON
Error handling
Authentication
Logging
Retries
```

## Project 6 — Production API

Add:

```text
Application structure
Configuration
Database
Validation
Authentication
Testing
Logging
Docker
CI/CD
```

---

# 🎤 Interview Questions

## Beginner

1. What is Python?
2. What is dynamic typing?
3. What are mutable and immutable objects?
4. What is the difference between list and tuple?
5. What is a dictionary?
6. What is a set?
7. What is the difference between `==` and `is`?
8. What does `None` mean?
9. What is a Python function?
10. What is a module?

## Intermediate

11. What are `*args` and `**kwargs`?
12. What is list comprehension?
13. What is a generator?
14. What is an iterator?
15. What is a decorator?
16. What is a context manager?
17. What is inheritance?
18. What is polymorphism?
19. What is encapsulation?
20. What is exception handling?

## Advanced

21. Explain Python's name-binding model.
22. Explain shallow vs deep copy.
23. Explain closures.
24. Explain decorators.
25. Explain MRO.
26. Explain descriptors.
27. What is duck typing?
28. What are protocols?
29. How does garbage collection work?
30. When would you use threads vs processes vs asyncio?

## Professional

31. How would you structure a large Python application?
32. How do you manage dependencies?
33. How do you design testable code?
34. How do you handle configuration?
35. How do you protect secrets?
36. How do you diagnose a slow Python application?
37. How would you design an API client?
38. How would you make a service observable?
39. How do you approach backwards compatibility?
40. How do you safely upgrade dependencies?

---

# 🔥 Python Gotchas to Understand

## Mutable objects

```python
items = []

a = items
b = items

b.append(1)

print(a)
```

Both names refer to the same list.

## Default arguments

Avoid mutable defaults:

```python
def func(items=[]):
    ...
```

Prefer:

```python
def func(items=None):
    if items is None:
        items = []
```

## Late binding in closures

Be careful when creating closures inside loops:

```python
functions = []

for i in range(3):
    functions.append(lambda: i)
```

All functions may observe the final loop value because of Python's closure/name lookup behavior.

One solution is binding the current value:

```python
functions = []

for i in range(3):
    functions.append(lambda i=i: i)
```

## Floating-point precision

```python
print(0.1 + 0.2)
```

Binary floating-point numbers do not represent every decimal fraction exactly.

For decimal financial calculations, investigate `decimal.Decimal`.

```python
from decimal import Decimal

total = Decimal("0.10") + Decimal("0.20")

print(total)
```

---

# 🧹 Code Quality Checklist

Before submitting Python code:

- [ ] Meaningful variable names
- [ ] Small, focused functions
- [ ] No unnecessary global state
- [ ] Correct exception handling
- [ ] Type hints where useful
- [ ] Tests for important behavior
- [ ] No secrets in source code
- [ ] Input validation where needed
- [ ] Logging for important operational events
- [ ] Dependencies documented
- [ ] Formatting/linting checks pass
- [ ] README/documentation updated
- [ ] No unnecessary premature optimization

---

# 📐 Recommended Development Workflow

```text
Understand the requirement
        ↓
Design the solution
        ↓
Write a small implementation
        ↓
Run it
        ↓
Write tests
        ↓
Refactor
        ↓
Lint / format
        ↓
Review
        ↓
Commit
        ↓
Automate checks in CI
```

---

# 🧪 Testing Pyramid

A healthy test strategy commonly contains:

```text
             /\
            /  \
           / E2E\
          /------\
         / Integr.\
        /----------\
       / Unit Tests \
      /______________\
```

In general:

- Many fast unit tests
- A useful set of integration tests
- Fewer expensive end-to-end tests

---

# 🔐 Security Basics

Never commit:

```text
API keys
Passwords
Private keys
Database credentials
Tokens
```

Bad:

```python
API_KEY = "my-secret-key"
```

Prefer environment/configuration management:

```python
import os

api_key = os.environ["API_KEY"]
```

Also:

- Validate untrusted input.
- Use parameterized SQL.
- Avoid unsafe deserialization.
- Keep dependencies updated.
- Use HTTPS for network services.
- Apply least privilege.

---

# ⚡ Performance Principles

Do not optimize based only on intuition.

Use:

```text
Measure
  ↓
Identify bottleneck
  ↓
Optimize
  ↓
Measure again
```

Useful modules/tools:

```python
timeit
cProfile
profile
tracemalloc
```

Example:

```python
import timeit

result = timeit.timeit(
    "sum(range(1000))",
    number=10_000
)

print(result)
```

---

# 📦 Packaging Checklist

A reusable Python package should generally have:

```text
pyproject.toml
README.md
LICENSE
src/
tests/
```

Before publishing:

- Define package metadata.
- Declare supported Python versions.
- Declare dependencies.
- Include tests.
- Include documentation.
- Choose an appropriate license.
- Build and test the package in a clean environment.

---

# 🌳 Recommended Git Workflow

```bash
git init
git add .
git commit -m "Initial Python learning repository"
```

Feature workflow:

```bash
git checkout -b feature/add-generators
```

After implementation:

```bash
git add .
git commit -m "Add generator examples"
```

Then open a pull request according to your team's workflow.

---

# 🤝 Contributing

Contributions are welcome.

Suggested process:

1. Fork the repository.
2. Create a feature branch.
3. Add or improve examples.
4. Add tests where appropriate.
5. Run formatting and linting.
6. Update documentation.
7. Submit a pull request.

Please keep examples:

- Simple
- Correct
- Readable
- Runnable
- Focused on one concept

---

# 📄 License

This project can be distributed under the MIT License.

Add a `LICENSE` file to the repository containing the license text you choose.

---

# ⭐ Learning Philosophy

Do not try to memorize every Python feature.

Focus on understanding:

```text
Why it exists
How it works
When to use it
When not to use it
How to test it
How to maintain it
```

The goal is not merely:

> "I know Python syntax."

The goal is:

> "I can use Python to design, build, test, debug, and maintain reliable software."

---

# 🎯 Final Roadmap

```text
                 PYTHON
                    │
        ┌───────────┴───────────┐
        │                       │
     BEGINNER              INTERMEDIATE
        │                       │
  Syntax / Types          Functions / OOP
  Collections             Files / JSON
  Conditions              Exceptions
  Loops                   Modules
        │                       │
        └───────────┬───────────┘
                    │
                 ADVANCED
                    │
       Generators / Decorators
       Context Managers
       Typing / Dataclasses
       Asyncio / Concurrency
       Descriptors / MRO
                    │
                    ↓
              PROFESSIONAL
                    │
       Testing / APIs / Databases
       Packaging / Security
       CI/CD / Docker
       Architecture / Performance
                    │
                    ↓
              PRODUCTION
```

---

## 🚀 Start Here

If you are completely new to Python:

```text
1. Basics
2. Variables
3. Strings
4. Collections
5. Conditions
6. Loops
7. Functions
8. Comprehensions
9. Files
10. Exceptions
11. OOP
12. Modules
13. Testing
14. APIs / Databases
15. Advanced Python
16. Production projects
```

**Code every day. Build projects. Break things. Debug them. Refactor them. Test them. Repeat.** 🐍
