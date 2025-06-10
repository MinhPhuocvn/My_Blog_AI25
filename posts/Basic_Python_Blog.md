# Basic Python
**Author:** Minh Phuoc  
**Date:** June 2025  

## 1. Introduction
Data types are fundamental in programming.  
They define the kind of value a variable can hold.  
In Python, these basic data types are used to store numbers, text, and logical values.

| **Data Type** | **Description** | **Examples** |
|--------------|---------------|-------------|
| `Integer`    | Whole numbers  | `1`, `-5`, `100` |
| `Float`      | Decimal numbers | `3.14`, `-0.01` |
| `String`     | Sequence of characters | `"Hello"`, `'Python'` |
| `Boolean`    | Logical values: true or false | `True`, `False` |

## 2. List in Python
A **list** is a collection used to store multiple items in a single variable.  
Lists can contain elements of any data type, and the items are **ordered and changeable**.

You can define a list using the following syntax:
```python
list_name = [element1, element2, ..., elementN]
```
Example:
```python
# Create a list of fruits
fruits = ["apple", "banana", "cherry"]
print(fruits[0])  # Output: apple
```

## 3. Dictionary in Python
A **dictionary** is a collection of key-value pairs.  
Each item in a dictionary has a **key** and a **value**, and the key is used to access the value.  
Dictionaries are **unordered**, **changeable**, and do not allow duplicate keys.

<p align="center">
    <img src="dictionary_syntax.png" alt="Structure of a Python function ">
</p>

**<p align="center">Figure 1: Dictionary syntax breakdown: key-value pairs inside curly brackets</p>**

Example:
```python
# Create a dictionary with student information
student = {
    "name": "Alice",
    "age": 20,
    "major": "Computer Science"
}

# Access the value using a key
print(student["name"])  # Output: Alice
```

## 4. Functions in Python
A **function** is a reusable block of code that performs a specific task.  
Functions help make your code organised, readable, and avoid repetition.

<p align="center">
    <img src="function_syntax.png" alt="Structure of a Python function ">
</p>

**<p align="center">Figure 2: Structure of a Python function</p>**

You can define a function in Python using the `def` keyword:
```python
# Define a simple function
def greet():
    print("Hello!")

# Call the function
greet()  # Output: Hello!
```

Functions can also take **parameters** and return values using the `return` keyword:
```python
# Function with parameters and return value
def add(a, b):
    return a + b

result = add(3, 5)
print(result)  # Output: 8
```

### Syntax Summary:
- `def function_name(parameters):` — defines a function.
- Indentation (usually 4 spaces) is required to define the function body.
- Use `return` to return a result from the function.

## 5. Branching in Python
Branching allows a program to make decisions based on conditions.  
This is commonly done using `if`, `elif`, and `else` statements.

### 5.1 Comparison Operators
Comparison operators are used to compare two values.  
They return a Boolean value: `True` or `False`.

| **Operator** | **Description** |
|-------------|---------------|
| `==` | Equal to |
| `!=` | Not equal to |
| `>`  | Greater than |
| `<`  | Less than |
| `>=` | Greater than or equal to |
| `<=` | Less than or equal to |

### 5.2 Using `if` Statements
The `if` statement allows you to execute code only if a certain condition is `True`.
```python
age = 18
if age >= 18:
    print("You are an adult.")
```

### Using `if-else`
You can use `else` to define an alternative block of code when the condition is not met.
```python
age = 16
if age >= 18:
    print("You are an adult.")
else:
    print("You are a minor.")
```

### Using `elif`
Use `elif` (else if) to check multiple conditions.
```python
score = 75
if score >= 90:
    print("Grade A")
elif score >= 80:
    print("Grade B")
elif score >= 70:
    print("Grade C")
else:
    print("Grade D or lower")
```

