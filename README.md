# PythonBasics

Python supports 2 basic concepts: variables and functions.

### How to define a variable?
Example:  
  x = 10  
  s = "Hello, world!"  
  s = 'This is also a string :)'  

Python is a dynamically typed interpreted programming language. Therefore, it is not necessary to specify the type of the variable at all. But if you want to, you can easily do it. For example:  
  x: int = 10  
  s: str = "Hello, world!"  

### How to define a function?

Oh, it's really simple to define a function in Python! Example:  
  
def print_sum(a, b):
    sum = a + b
    print(sum)  

It's not a secret that Python functions can return some variables. But how?  
By default, any Python function returns None (equivalent to null/nil in other programming languages). To return something meaningful, you should implicitly write it like this:

def add(a, b):
    return a + b

### I can't see ";" in this Python code! Where is it?
It's a simple question that has a simple answer, my friend. Python doesn't use any ; at all!
