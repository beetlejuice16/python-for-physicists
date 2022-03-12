# What is meant by type?

Before understanding what a type is, one should know the concept of a variable. 

A variable in programing can be compared to a box that holds a piece of information. Variables are very useful, as they can store information that can be used to solve an problem.

Usually to use these variables, one should define what type of variable it is. Some of the most used types are:

1) Integers `int`
2) Float `float`
3) Strings `str`
4) Booleans `bool`
5) Lists `list`
6) Sets `set`
7) Dictionaries `dict`

Most programing languages don't allow the change of a type of variable. Once set it can no longer be changed. However, in python this isn't the case. One can change an int to a list to a bool to a list again. This isn't recommended since it makes the code confusing, and slows down the script.

# Defining the type

In Python defining the type of variable isn't done that often. However, it is recommended to define the type of the variable once you set it. This has multiple upsides in Python:

1) More readable scripts. Which is something to consider, especially when working in a group where multiple people are going to read the code.
2) Scripts run faster as Python doesn't need to check the type of the variable and can just use what you gave it.

To define the type of a variable it is as follows:

```python
x: int = 3
y: float = 4.2
my_bool: bool = true
my_list: list = [1, 2, 3, 4, 5]
```

# Integers

Like it name suggests, an integer is 