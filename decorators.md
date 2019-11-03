## Decorators

* In Python, functions are the first class [objects](objects.md)
    * Functions are [objects](objects.md); they can be referenced to, passed to a variable and returned from other functions as well.
    * Functions can be defined inside another function and can also be passed as argument to another function.
* It allows programmers to modify the behavior of function or class. 
* Decorators allow us to wrap another function in order to extend the behavior of wrapped function, without permanently modifying it.
* In Decorators, functions are taken as the argument into another function and then called inside the wrapper function.

**Example:**

@DecoratorExample

def func():

    print("Function")

func()

Go back to [README](README.md)