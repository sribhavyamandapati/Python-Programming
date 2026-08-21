# 🐍 Python Programming 

Python is a **high-level, interpreted, general-purpose programming language** known for its simple syntax and readability.

Python is widely used in:

- 🤖 Artificial Intelligence (AI)
- 🧠 Machine Learning (ML)
- 📊 Data Science
- 🌐 Web Development
- 📈 Data Analysis
- 🔍 Automation
- 👁️ Computer Vision
- 🧬 Deep Learning
- ⚙️ Software Development

Python allows developers to write programs using fewer lines of code compared with many other programming languages.

---

# 🤖 Why is Python Used for AI?

Python is one of the most popular programming languages for Artificial Intelligence and Machine Learning.

## 1. Simple and Readable Syntax

Python syntax is easy to understand and is close to normal English.

```python
name = "Bhavya"
print(name)
```

This makes Python easier to learn, read, write, debug, and maintain.

## 2. Large Number of Libraries

Python provides many powerful libraries for AI and Data Science.

| Library | Purpose |
|---|---|
| NumPy | Numerical calculations |
| Pandas | Data manipulation |
| Matplotlib | Data visualization |
| Scikit-learn | Machine Learning |
| TensorFlow | Deep Learning |
| PyTorch | Deep Learning |
| OpenCV | Computer Vision |

## 3. Large Community

Python has a huge developer community. Developers can easily find documentation, tutorials, libraries, and solutions to common problems.

## 4. Easy Integration

Python can work with databases, APIs, web applications, cloud platforms, and other programming languages.

## 5. Faster Development

Python allows developers to create applications and AI models using relatively less code.

---

# 📖 Python Variables

A **variable** is a name used to store or refer to a value in memory.

```python
name = "Bhavya"
age = 21
salary = 50000
```

Here:

```text
name   → "Bhavya"
age    → 21
salary → 50000
```

Variables allow us to store values and use those values later in the program.

```python
name = "Bhavya"

print(name)
print(name)
```

Output:

```text
Bhavya
Bhavya
```

## Variable Naming Rules

### Rule 1: Variable names can contain letters, numbers and `_`

```python
student_name = "Bhavya"
student1 = "Ravi"
```

### Rule 2: A variable cannot start with a number

❌ Invalid:

```python
1student = "Bhavya"
```

✅ Valid:

```python
student1 = "Bhavya"
```

### Rule 3: Spaces are not allowed

❌ Invalid:

```python
student name = "Bhavya"
```

✅ Use underscore:

```python
student_name = "Bhavya"
```

### Rule 4: Python is case-sensitive

```python
name = "Bhavya"
Name = "Ravi"
```

`name` and `Name` are different variables.

### Rule 5: Do not use Python keywords as variable names

Examples:

```text
if
else
class
for
while
def
```

These should not be used as variable names.

---

# 🔢 Python Data Types

A data type tells Python what kind of value is being stored.

The commonly used basic data types are:

- `int`
- `float`
- `str`
- `bool`

## 1. Integer (`int`)

Integers are whole numbers.

```python
age = 21
marks = 95

print(type(age))
```

Output:

```text
<class 'int'>
```

## 2. Float (`float`)

Float represents decimal numbers.

```python
price = 250.50
percentage = 85.5
```

## 3. String (`str`)

A string represents text.

```python
name = "Bhavya"
city = "Guntur"
```

Strings can be written using:

```python
"Hello"
'Hello'
```

## 4. Boolean (`bool`)

Boolean values represent either `True` or `False`.

```python
is_student = True
is_employee = False
```

Boolean values are commonly used in conditions.

---

# 🔄 Type Conversion

Type conversion means changing one data type into another.

Common conversion functions are:

```python
int()
float()
str()
bool()
```

## String to Integer

```python
age = "21"

age = int(age)

print(age)
print(type(age))
```

## Integer to Float

```python
number = 10

number = float(number)

print(number)
```

Output:

```text
10.0
```

## Integer to String

```python
age = 21

age = str(age)

print(type(age))
```

Output:

```text
<class 'str'>
```

## Float to Integer

```python
price = 99.99

price = int(price)

print(price)
```

Output:

```text
99
```

The decimal part is removed.

---

# 📦 Python Built-in Collection Data Types

Python provides powerful built-in collection types:

1. List
2. Tuple
3. Set
4. Dictionary

---

# 📋 List

A **list** stores multiple values in a single variable.

Lists are:

- Ordered
- Mutable
- Allow duplicate values

```python
fruits = ["apple", "banana", "mango"]

print(fruits)
```

## List Methods and Functions

| Function / Method | Description | Example |
|---|---|---|
| `append()` | Adds an element at the end | `numbers.append(40)` |
| `insert()` | Adds an element at a specific index | `numbers.insert(1, 15)` |
| `extend()` | Adds multiple elements | `numbers.extend([50, 60])` |
| `remove()` | Removes the specified value | `numbers.remove(20)` |
| `pop()` | Removes and returns an element | `numbers.pop()` |
| `clear()` | Removes all elements | `numbers.clear()` |
| `index()` | Returns the index of a value | `numbers.index(30)` |
| `count()` | Counts occurrences of a value | `numbers.count(20)` |
| `sort()` | Sorts the list | `numbers.sort()` |
| `reverse()` | Reverses the list | `numbers.reverse()` |
| `copy()` | Creates a copy | `new = numbers.copy()` |
| `len()` | Returns number of elements | `len(numbers)` |
| `max()` | Returns largest value | `max(numbers)` |
| `min()` | Returns smallest value | `min(numbers)` |
| `sum()` | Returns sum of numeric elements | `sum(numbers)` |

### Example

```python
numbers = [10, 20, 30]

numbers.append(40)
numbers.insert(1, 15)

print(numbers)
```

Output:

```text
[10, 15, 20, 30, 40]
```

---

# 📦 Tuple

A **tuple** stores multiple values.

Tuples are:

- Ordered
- Immutable
- Allow duplicate values

```python
coordinates = (10, 20)
```

Because tuples are immutable, their values cannot normally be changed after creation.

## Tuple Methods and Functions

| Function / Method | Description | Example |
|---|---|---|
| `count()` | Counts occurrences of a value | `numbers.count(20)` |
| `index()` | Returns the index of a value | `numbers.index(30)` |
| `len()` | Returns number of elements | `len(numbers)` |
| `max()` | Returns largest value | `max(numbers)` |
| `min()` | Returns smallest value | `min(numbers)` |
| `sum()` | Returns sum of numeric elements | `sum(numbers)` |
| `sorted()` | Returns sorted data as a list | `sorted(numbers)` |

### Example

```python
numbers = (10, 20, 30, 20)

print(numbers.count(20))
print(numbers.index(30))
```

Output:

```text
2
2
```

### Important Point

Tuple has only two main methods:

```text
count()
index()
```

Functions such as `len()`, `max()`, `min()`, `sum()` and `sorted()` are built-in Python functions, not tuple methods.

---

# 🔵 Set

A **set** is an unordered, mutable collection that stores unique values.

```python
numbers = {10, 20, 30, 20}

print(numbers)
```

The duplicate `20` is removed.

```text
{10, 20, 30}
```

## Set Methods and Functions

| Function / Method | Description | Example |
|---|---|---|
| `add()` | Adds one element | `numbers.add(40)` |
| `update()` | Adds multiple elements | `numbers.update([50, 60])` |
| `remove()` | Removes an element; raises an error if absent | `numbers.remove(20)` |
| `discard()` | Removes an element without error if absent | `numbers.discard(20)` |
| `pop()` | Removes and returns an arbitrary element | `numbers.pop()` |
| `clear()` | Removes all elements | `numbers.clear()` |
| `copy()` | Creates a copy | `new = numbers.copy()` |
| `union()` | Combines two sets | `a.union(b)` |
| `intersection()` | Returns common elements | `a.intersection(b)` |
| `difference()` | Returns elements only in first set | `a.difference(b)` |
| `symmetric_difference()` | Returns elements present in either set but not both | `a.symmetric_difference(b)` |
| `issubset()` | Checks whether one set is a subset of another | `a.issubset(b)` |
| `issuperset()` | Checks whether one set contains another | `a.issuperset(b)` |
| `isdisjoint()` | Checks whether sets have no common elements | `a.isdisjoint(b)` |
| `len()` | Returns number of elements | `len(numbers)` |

### Example

```python
a = {1, 2, 3}
b = {3, 4, 5}

print(a.union(b))
print(a.intersection(b))
print(a.difference(b))
```

Output:

```text
{1, 2, 3, 4, 5}
{3}
{1, 2}
```

---

# 📖 Dictionary

A **dictionary** stores data in **key-value pairs**.

```python
student = {
    "name": "Bhavya",
    "age": 21,
    "marks": 90
}
```

Here:

```text
"name"   → key
"Bhavya" → value
```

## Dictionary Methods and Functions

| Function / Method | Description | Example |
|---|---|---|
| `keys()` | Returns all keys | `student.keys()` |
| `values()` | Returns all values | `student.values()` |
| `items()` | Returns key-value pairs | `student.items()` |
| `get()` | Returns value for a key | `student.get("name")` |
| `update()` | Adds or updates key-value pairs | `student.update({"age": 22})` |
| `pop()` | Removes a specified key | `student.pop("age")` |
| `popitem()` | Removes the last inserted key-value pair | `student.popitem()` |
| `clear()` | Removes all elements | `student.clear()` |
| `copy()` | Creates a copy | `new = student.copy()` |
| `setdefault()` | Returns value; inserts key if absent | `student.setdefault("city", "Guntur")` |
| `fromkeys()` | Creates dictionary using given keys | `dict.fromkeys(["a", "b"])` |
| `len()` | Returns number of key-value pairs | `len(student)` |

### Example

```python
student = {
    "name": "Bhavya",
    "age": 21,
    "marks": 90
}

print(student.get("name"))

student.update({"age": 22})

print(student)
```

Output:

```text
Bhavya
{'name': 'Bhavya', 'age': 22, 'marks': 90}
```

---

# 🔤 String

A **string** is a sequence of characters enclosed within single quotes, double quotes, or triple quotes.

```python
name = "Python"
```

Strings are **immutable**, meaning the original string cannot be changed directly.

## String Methods

| Method | Description | Example | Result |
|---|---|---|---|
| `upper()` | Converts to uppercase | `"python".upper()` | `PYTHON` |
| `lower()` | Converts to lowercase | `"PYTHON".lower()` | `python` |
| `capitalize()` | Capitalizes first character | `"python".capitalize()` | `Python` |
| `title()` | Capitalizes first letter of each word | `"hello python".title()` | `Hello Python` |
| `swapcase()` | Changes uppercase to lowercase and vice versa | `"PyThOn".swapcase()` | `pYtHoN` |
| `strip()` | Removes leading/trailing whitespace | `" hello ".strip()` | `hello` |
| `lstrip()` | Removes leading whitespace | `" hello".lstrip()` | `hello` |
| `rstrip()` | Removes trailing whitespace | `"hello ".rstrip()` | `hello` |
| `replace()` | Replaces a substring | `"hello".replace("h","H")` | `Hello` |
| `split()` | Splits string into a list | `"a,b,c".split(",")` | `['a', 'b', 'c']` |
| `join()` | Joins elements into a string | `"-".join(["A","B"])` | `A-B` |
| `find()` | Returns position of substring | `"python".find("t")` | `2` |
| `index()` | Returns position of substring | `"python".index("t")` | `2` |
| `count()` | Counts occurrences | `"banana".count("a")` | `3` |
| `startswith()` | Checks starting characters | `"Python".startswith("Py")` | `True` |
| `endswith()` | Checks ending characters | `"Python".endswith("on")` | `True` |
| `isalpha()` | Checks whether all characters are alphabets | `"Python".isalpha()` | `True` |
| `isdigit()` | Checks whether all characters are digits | `"123".isdigit()` | `True` |
| `isalnum()` | Checks whether characters are letters/numbers | `"Python123".isalnum()` | `True` |
| `isspace()` | Checks whether all characters are whitespace | `"   ".isspace()` | `True` |
| `islower()` | Checks whether all letters are lowercase | `"python".islower()` | `True` |
| `isupper()` | Checks whether all letters are uppercase | `"PYTHON".isupper()` | `True` |

### String Example

```python
text = "hello python"

print(text.upper())
print(text.lower())
print(text.title())
print(text.replace("python", "world"))
```

Output:

```text
HELLO PYTHON
hello python
Hello Python
hello world
```

---

# 🧮 Important Python Built-in Functions

Python provides built-in functions that can work with different data types.

| Built-in Function | Purpose | Example | Result |
|---|---|---|---|
| `len()` | Returns number of elements or characters | `len("Python")` | `6` |
| `type()` | Returns the data type | `type(10)` | `<class 'int'>` |
| `int()` | Converts to integer | `int("10")` | `10` |
| `float()` | Converts to float | `float("10.5")` | `10.5` |
| `str()` | Converts to string | `str(100)` | `"100"` |
| `bool()` | Converts to Boolean | `bool(1)` | `True` |
| `list()` | Converts to list | `list("ABC")` | `['A', 'B', 'C']` |
| `tuple()` | Converts to tuple | `tuple([1, 2])` | `(1, 2)` |
| `set()` | Converts to set | `set([1, 2, 2])` | `{1, 2}` |
| `dict()` | Creates a dictionary | `dict(name="Bhavya")` | `{'name': 'Bhavya'}` |
| `max()` | Returns maximum value | `max([10,20,30])` | `30` |
| `min()` | Returns minimum value | `min([10,20,30])` | `10` |
| `sum()` | Returns sum | `sum([10,20,30])` | `60` |
| `sorted()` | Returns sorted data | `sorted([3,1,2])` | `[1,2,3]` |
| `abs()` | Returns absolute value | `abs(-10)` | `10` |
| `round()` | Rounds a number | `round(10.567, 2)` | `10.57` |
| `range()` | Generates a sequence | `range(1,5)` | `1,2,3,4` |
| `enumerate()` | Adds an index to an iterable | `enumerate(["A","B"])` | index + value |
| `zip()` | Combines multiple iterables | `zip([1,2],["A","B"])` | paired values |

---

# 🔎 Method vs Built-in Function

This distinction is important.

## Method

A method is called using the object.

```python
name = "python"

name.upper()
name.lower()
```

Here:

```text
upper() → String method
lower() → String method
```

## Built-in Function

A built-in function is called directly.

```python
len(name)
type(name)
```

Here:

```text
len()  → Built-in function
type() → Built-in function
```

### Easy Way to Remember

```text
object.method()

name.upper()
numbers.append(10)
student.keys()
```

versus:

```text
function(object)

len(name)
type(name)
max(numbers)
```

---

# 📊 Collection Data Types — Quick Comparison

| Data Type | Ordered | Mutable | Allows Duplicates | Main Usage |
|---|---|---|---|---|
| List | ✅ Yes | ✅ Yes | ✅ Yes | Collection of changeable values |
| Tuple | ✅ Yes | ❌ No | ✅ Yes | Fixed collection of values |
| Set | ❌ No | ✅ Yes | ❌ No | Unique values and set operations |
| Dictionary | ✅ Yes* | ✅ Yes | Keys ❌ / Values ✅ | Key-value data |
| String | ✅ Yes | ❌ No | ✅ Yes | Text and characters |

`*` Dictionaries preserve insertion order in modern Python versions.

---

# 🌍 Real-Time Examples

| Data Type | Real-Time Example |
|---|---|
| List | Shopping cart items |
| Tuple | GPS coordinates `(latitude, longitude)` |
| Set | Unique email addresses |
| Dictionary | Student information |
| String | Name, address, message |

```python
# List
shopping_cart = ["Laptop", "Mouse", "Keyboard"]

# Tuple
location = (16.3067, 80.4365)

# Set
unique_numbers = {10, 20, 30}

# Dictionary
student = {
    "name": "Bhavya",
    "age": 21,
    "course": "B.Tech"
}

# String
message = "Welcome to Python"
```

---

# 🔁 For Loop

A `for` loop is used to repeat a block of code for each item in a sequence.

## Syntax

```python
for variable in sequence:
    statements
```

## Example

```python
numbers = [10, 20, 30, 40]

for number in numbers:
    print(number)
```

Output:

```text
10
20
30
40
```

---

# 🔄 While Loop

A `while` loop executes a block of code as long as a condition is `True`.

## Syntax

```python
while condition:
    statements
```

## Example

```python
count = 1

while count <= 5:
    print(count)
    count += 1
```

Output:

```text
1
2
3
4
5
```

---

# 🚦 Control Flow Statements

Control flow statements determine which part of the program should execute.

Important control flow statements include:

- `if`
- `if-else`
- `if-elif-else`
- `break`
- `continue`

## `if` Statement

Used when a block should execute only when a condition is true.

```python
age = 20

if age >= 18:
    print("Eligible to vote")
```

## `if-else`

Used when there are two possible outcomes.

```python
age = 16

if age >= 18:
    print("Eligible")
else:
    print("Not Eligible")
```

## `if-elif-else`

Used when multiple conditions need to be checked.

```python
marks = 85

if marks >= 90:
    print("A+")
elif marks >= 75:
    print("A")
elif marks >= 60:
    print("B")
else:
    print("C")
```

---

# 🛑 Break Statement

`break` immediately terminates the loop.

```python
for i in range(1, 10):

    if i == 5:
        break

    print(i)
```

Output:

```text
1
2
3
4
```

---

# ⏭️ Continue Statement

`continue` skips the current iteration and moves to the next iteration.

```python
for i in range(1, 6):

    if i == 3:
        continue

    print(i)
```

Output:

```text
1
2
4
5
```

---

# 🧩 Functions

A function is a reusable block of code designed to perform a specific task.

Functions help with:

- Code reusability
- Better organization
- Reduced duplicate code
- Easier maintenance

## Function Definition

```python
def function_name():
    statements
```

## Example

```python
def greet():
    print("Hello Bhavya")

greet()
```

---

# 📌 Function With Parameters

```python
def add(a, b):
    return a + b

result = add(10, 20)

print(result)
```

Output:

```text
30
```

---

# 📚 Types of Functions

## 1. Function Without Arguments

```python
def greet():
    print("Hello")
```

## 2. Function With Arguments

```python
def greet(name):
    print("Hello", name)
```

## 3. Function With Return Value

```python
def add(a, b):
    return a + b
```

## 4. Function With Default Arguments

```python
def greet(name="User"):
    print("Hello", name)
```

## 5. Lambda Function

---

# ⚡ Lambda Function

A lambda function is a small anonymous function.

## Syntax

```python
lambda arguments: expression
```

## Example

```python
square = lambda x: x * x

print(square(5))
```

Output:

```text
25
```

Lambda functions are useful when a small function is required temporarily.

---

# 🗺️ map() Function

`map()` applies a function to every element of an iterable.

```python
numbers = [1, 2, 3, 4]

result = map(lambda x: x * 2, numbers)

print(list(result))
```

Output:

```text
[2, 4, 6, 8]
```

---

# 🔍 filter() Function

`filter()` selects elements based on a condition.

```python
numbers = [1, 2, 3, 4, 5, 6]

result = filter(lambda x: x % 2 == 0, numbers)

print(list(result))
```

Output:

```text
[2, 4, 6]
```

---

# ➕ reduce() Function

`reduce()` repeatedly applies a function to elements and produces a single result.

It is available in the `functools` module.

```python
from functools import reduce

numbers = [1, 2, 3, 4]

result = reduce(lambda x, y: x + y, numbers)

print(result)
```

Output:

```text
10
```

---

# ⚠️ Exception Handling

Exception handling is used to handle runtime errors without abruptly terminating the program.

Python commonly uses:

```text
try
except
else
finally
```

## Example

```python
try:
    number = int(input("Enter a number: "))

    result = 10 / number

    print(result)

except ValueError:
    print("Please enter a valid number")

except ZeroDivisionError:
    print("Cannot divide by zero")
```

## `try`

Contains code that may produce an exception.

## `except`

Handles the exception.

## `else`

Executes when no exception occurs.

## `finally`

Executes whether an exception occurs or not.

```python
try:
    print("Program running")

except Exception:
    print("Error occurred")

finally:
    print("Program completed")
```

---

# 📁 File Handling

File handling is used to:

- Create files
- Read files
- Write files
- Append data
- Store information permanently

Python provides the `open()` function.

## Basic Syntax

```python
file = open("example.txt", "r")
```

## Common File Modes

| Mode | Meaning |
|---|---|
| `r` | Read |
| `w` | Write |
| `a` | Append |
| `x` | Create |

---

# 🔐 Why Use `with open()`?

Instead of manually opening and closing a file:

```python
file = open("example.txt", "r")

data = file.read()

file.close()
```

we can use:

```python
with open("example.txt", "r") as file:
    data = file.read()
```

The `with` statement automatically closes the file after the block is completed, including when an exception occurs.

---

# ✍️ Writing to a File

```python
with open("example.txt", "w") as file:
    file.write("Hello Python")
```

---

# 📖 Reading a File

```python
with open("example.txt", "r") as file:
    data = file.read()

print(data)
```

---

# 💾 pickle — dump, dumps, load and loads

Python's `pickle` module can serialize Python objects.

It is commonly used to save trained Machine Learning models.

```python
import pickle
```

## `dump()`

Saves an object into a file.

```python
import pickle

model = {"name": "Linear Regression"}

with open("model.pkl", "wb") as file:
    pickle.dump(model, file)
```

## `load()`

Loads an object from a file.

```python
with open("model.pkl", "rb") as file:
    model = pickle.load(file)

print(model)
```

## `dumps()`

Converts an object into a serialized bytes object in memory.

```python
data = pickle.dumps(model)
```

## `loads()`

Converts serialized bytes back into a Python object.

```python
model = pickle.loads(data)
```

## Simple Difference

```text
dump()  → object → file
load()  → file → object

dumps() → object → bytes
loads() → bytes → object
```

> ⚠️ Never unpickle data from an untrusted source because deserialization can execute malicious code.

---

# 🏗️ Object-Oriented Programming (OOP)

OOP stands for **Object-Oriented Programming**.

OOP is a programming approach based on **classes and objects**.

OOP helps developers create reusable, organized, maintainable, and secure code.

OOP is especially useful for large applications.

---

# 🌍 Real-Time Example of OOP

Consider a **Car**.

A car has:

## Properties

```text
brand
color
model
speed
```

## Behaviors

```text
start()
stop()
accelerate()
brake()
```

In Python, we can represent this using a class.

---

# 🏛️ Class

A class is a blueprint or template used to create objects.

```python
class Car:

    def __init__(self, brand, color):
        self.brand = brand
        self.color = color

    def start(self):
        print("Car started")
```

The `Car` class defines the structure and behavior of a car.

---

# 🚗 Object

An object is an instance of a class.

```python
car1 = Car("Toyota", "Red")
car2 = Car("Honda", "Blue")
```

Here:

```text
Car  → Class
car1 → Object
car2 → Object
```

The same class can be used to create many objects.

---

# 👤 Self Keyword

`self` refers to the **current object**.

```python
class Student:

    def __init__(self, name, age):
        self.name = name
        self.age = age
```

When:

```python
student1 = Student("Bhavya", 21)
```

Python uses `self` to associate `name` and `age` with `student1`.

For another object:

```python
student2 = Student("Ravi", 22)
```

`self` refers to `student2`.

---

# 🏗️ Constructor

A constructor is a special method that is automatically called when an object is created.

In Python, the commonly used constructor is:

```python
__init__()
```

## Example

```python
class Student:

    def __init__(self, name, age):
        self.name = name
        self.age = age

student = Student("Bhavya", 21)

print(student.name)
print(student.age)
```

Output:

```text
Bhavya
21
```

The constructor initializes the object's data.

---

# ⭐ Four Basic Building Blocks of Python OOP

For understanding Python OOP, four important concepts are:

1. Class
2. Object
3. `self`
4. Constructor

These form the basic foundation for creating and working with objects in Python.

---

# 🧬 Four Main Pillars of OOP

The four major pillars of Object-Oriented Programming are:

1. Encapsulation
2. Inheritance
3. Polymorphism
4. Abstraction

---

# 1. 🛡️ Encapsulation

Encapsulation means **bundling data and methods together inside a class** and controlling how the data is accessed.

## Real-Time Example

A bank account contains sensitive information such as balance. We should not allow every part of the program to directly modify the balance without rules.

```python
class BankAccount:

    def __init__(self, balance):
        self.__balance = balance

    def get_balance(self):
        return self.__balance

    def deposit(self, amount):
        if amount > 0:
            self.__balance += amount
```

Here:

```python
__balance
```

is treated as a private attribute.

Encapsulation helps protect the internal state of an object.

---

# 2. 🧬 Inheritance

Inheritance allows one class to acquire properties and methods from another class.

It promotes **code reuse**.

## Real-Time Example

```text
Vehicle
   ↓
Car
   ↓
ElectricCar
```

## Example

```python
class Vehicle:

    def start(self):
        print("Vehicle started")


class Car(Vehicle):

    def drive(self):
        print("Car is driving")


car = Car()

car.start()
car.drive()
```

The `Car` class inherits the `start()` method from `Vehicle`.

## Benefits

- Code reusability
- Less duplicate code
- Easier maintenance
- Represents parent-child relationships

---

# 3. 🔄 Polymorphism

Polymorphism means **one interface or method name can have different behaviors depending on the object**.

## Real-Time Example

Different animals make different sounds.

```python
class Dog:

    def sound(self):
        print("Bark")


class Cat:

    def sound(self):
        print("Meow")


animals = [Dog(), Cat()]

for animal in animals:
    animal.sound()
```

Output:

```text
Bark
Meow
```

The same method:

```python
sound()
```

behaves differently for different objects.

---

# 4. 🎭 Abstraction

Abstraction means **hiding implementation details and exposing only the necessary functionality**.

## Real-Time Example

When using an ATM, the user sees options such as:

```text
Withdraw
Deposit
Check Balance
```

The user does not need to know the internal implementation of the banking system.

Python provides abstraction using the `abc` module.

```python
from abc import ABC, abstractmethod


class Vehicle(ABC):

    @abstractmethod
    def start(self):
        pass


class Car(Vehicle):

    def start(self):
        print("Car starts using an engine")
```

The abstract class defines what the child class must implement.

---

# 📚 OOP Summary

| Concept | Meaning | Real-Time Example |
|---|---|---|
| Class | Blueprint | Car design |
| Object | Instance of class | A particular car |
| `self` | Current object reference | Current car |
| Constructor | Initializes object | Car creation |
| Encapsulation | Protects/bundles data | Bank account |
| Inheritance | Reuses parent functionality | Car → Vehicle |
| Polymorphism | Same interface, different behavior | Dog/Cat sound |
| Abstraction | Hides implementation details | ATM |

---

# 🧠 Why OOP is Important

OOP is useful because it provides:

## ♻️ Code Reusability

Existing classes and methods can be reused.

## 🔐 Data Protection

Encapsulation helps control access to internal data.

## 🧩 Modularity

Large programs can be divided into smaller classes.

## 🔧 Maintainability

Changes can be made more easily.

## 📈 Scalability

OOP is useful when developing large applications.

---



---

# 🤖 Python for Machine Learning and AI

After learning Python fundamentals, Python can be used to build AI and Machine Learning applications.

A typical Machine Learning workflow is:

```text
Python
  ↓
NumPy / Pandas
  ↓
Data Cleaning
  ↓
Data Visualization
  ↓
Feature Engineering
  ↓
Machine Learning
  ↓
Model Training
  ↓
Model Evaluation
  ↓
Prediction
  ↓
Flask / Web Application
```

## Example: House Price Prediction

Python can be used to build a House Price Prediction application:

```text
Dataset
   ↓
Pandas
   ↓
Data Cleaning
   ↓
Feature Conversion
   ↓
Train/Test Split
   ↓
Linear Regression
   ↓
Model Training
   ↓
pickle
   ↓
Flask
   ↓
Web Application
   ↓
House Price Prediction
```

---

# 🎯 Conclusion

Python provides a simple and powerful programming environment for beginners as well as professional developers.

Learning Python from the fundamentals is important before moving into advanced areas such as:

- Machine Learning
- Artificial Intelligence
- Data Science
- Deep Learning
- Computer Vision
- Generative AI
- Web Development
- Automation

A strong understanding of **variables, data types, collections, loops, conditions, functions, exception handling, file handling, and OOP** provides a strong foundation for developing real-world Python applications.

---




