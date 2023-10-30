# Python_DevOps_Functions_Modules_Packages

## 1. Differences Between Functions, Modules, and Packages

### Functions
 
A function in Python is a block of code that performs a specific task. Functions are defined using the `def` keyword and can take inputs, called arguments. They are a way to encapsulate and reuse code.
 
**Example:** 

```python
def greet(name):
    return f"Hello, {name}!"

message = greet("Alice")
print(message) 
``` 

In this example, `greet` is a function that takes a `name` argument and returns a greeting message.

Functions provide below advantages:
- Re-usability
- Readability
- Debugging


### Modules

A module is a Python script containing Python code. It can define functions, classes, and variables that can be used in other Python scripts. Modules help organize and modularize your code, making it more maintainable.

**Example:**

Suppose you have a Python file named `my_module.py`:

```python
# my_module.py
def square(x):
    return x ** 2

pi = 3.14159265
```

You can use this module in another script:

```python
import my_module

result = my_module.square(5)
print(result)
print(my_module.pi)
```

In this case, `my_module` is a Python module containing the `square` function and a variable `pi`.
