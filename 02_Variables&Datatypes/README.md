# Class 2: Variables and DataTypes (focus on string)


## Table of Contents

- [Variables](#variables)
- [Naming Conventions for Variables](#naming-conventions-for-variables)
- [Data Types](#data-types)
- [String Definitions](#string-definitions)
- [String Formatting](#string-formatting)
  - [Basic Techniques](#basic-techniques)
  - [Advanced Techniques](#advanced-techniques)
- [Naming Conventions](#naming-conventions)


## Variables:
In Python, a variable is a named container that can hold data. You can think of variables as labels or references to values.

## Naming Conventions for Variables:

* Variable names are case-sensitive. my_variable and My_Variable are different variables.
* Variable names must start with a letter (a-z, A-Z) or an underscore (_).
* After the initial letter, variable names can contain letters, digits (0-9), and underscores.
* It's best to use descriptive names to make your code more readable. For example, counter is more descriptive than c.
* Avoid using Python's reserved words (e.g., for, if, while) as variable names.

## Data Types
Python has several built-in data types. The core data types include:

1. int  (integer)
2. float
3. str  (float)
4. bool (boolean)
5. list
6. tuple
7. dict (dictionary)
8. set
9. None (None Type)
## String Definitions

### Single Quotes

You can define a string with single quotes.

```python
my_string: str = 'Hello, World!'
```

### Double Quotes

Alternatively, you can define a string with double quotes.

```python
my_string: str = "Hello, World!"
```

### Triple Single Quotes

Triple single quotes allow for string definitions that span multiple lines.

```python
my_string: str = '''Hello,
World!'''
```

### Triple Double Quotes

Like triple single quotes, triple double quotes also allow for multi-line string definitions.

```python
my_string: str = """Hello,
World!"""
```

## String Formatting

### Basic Techniques

#### Using `%s` and `%d`

You can use `%s` for string and `%d` for integers.

```python
name: str = "Alice"
age: int = 30
print("My name is %s and I am %d years old." % (name, age))
```

#### Using `.format()`

The `.format()` method is another way to format your strings.

```python
name: str = "Alice"
age: int = 30
print("My name is {} and I am {} years old.".format(name, age))
```

#### Using f-string (Python 3.6+)

f-strings provide a concise and readable way to include the value of Python expressions inside strings.

```python
name: str = "Alice"
age: int = 30
print(f"My name is {name} and I am {age} years old.")
```

### Advanced Techniques

#### f-string Expressions

You can include Python expressions within f-strings.

```python
x: int = 10
y: int = 20
print(f"The sum of {x} and {y} is {x+y}.")
```

#### f-string with Format Specification

You can format numbers using f-strings.

```python
pi: float = 3.14159
print(f"Value of pi to 2 decimal places: {pi:.2f}")
```

## Naming Conventions

### Variables

- Use `snake_case` for variable names.
  
```python
my_variable: int = 10
```

### Constants

- Use `UPPER_SNAKE_CASE` for constants.

```python
PI: float = 3.14159
```

