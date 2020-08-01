# Variables

A *variable* is simply a placeholder for information that may vary (change).

The naming rules for Python *variables* are:

* The variable name ust start with a letter or underscore (_).
* After the first letter you can use letters, numbers, or underscores.
* Variable names are case-sensitive, so once you make up a name, any other reference to that variable must use the same uppercase and lowercase letters as the name you originally made up.
* Variable names cannot be enclosed in, or contain, single or double quotation marks.
* PEP 8 style conventions recommend using only lowercase letters in variable names, use an underscore to separate multiple words in the variable name: variable_name.

## Creating variables
To create a variable, use the following syntax:
```python
variable_name = value
```
The value is whatever you want to store in the variable. It can be a number, a string or a Boolean True or False value.
The **=** sign in the *assignment operator* is so named because it assigns the value (on the right) to the variable (on the left). For example:
```python
x = 10
```

## Manipulating Variables
Much of programming revolves around storing values in variables and manipulating that information with operators.
```python
# this variable contains an integer
quantity = 10

# this variable contains a float
unit_price = 1.99

# this variable contains the result of multiplying quantity times unit_price
extended_price = quantity * unit_price

# display results
print(extended_price)
```