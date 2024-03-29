# Python Interview Questions
### Table of Contents

| No. | Questions |
| --- | --------- |
|   | **Introduction** |
|1  | [What does the Zen of Python mean?](#what-does-the-zen-of-python-mean)|
|2  | [What does PEP 8 mean?](#what-does-pep-8-mean)|
|   | **Core Python** |
|3  | [First Class functions in Python](#first-class-functions-in-python)|
|4  | [Python Anonymous/Lambda Function](#python-anonymous/lambda-function)|
|5  | [Decorators in Python](#decorators-in-python)
|6  | [Generators in Python](#generators-in-Python)
|7  | [Difference between == and is operator in Python](#difference-between-==-and-is-operator-in-Python)
|8  | [Python Shallow Copy and Deep Copy?](#python-shallow-copy-and-deep-copy)
|10 | [Context manager in python](#context-manager-in-python)
|   | **Python OOP** |
|   | **Others** |
|   | [Monkey Patching in Python (Dynamic Behavior)](#monkey-patching-in-python-dynamic-behavior) |



## Introduction

1. ### What does the Zen of Python mean?

    The Zen of Python is a collection of 19 "guiding principles" for writing computer programs that influence the design of the Python programming language. Software engineer Tim Peters wrote this set of principles and posted it on the Python mailing list in 1999. [More details..](https://en.wikipedia.org/wiki/Zen_of_Python)

   **[⬆ Back to Top](#table-of-contents)**


2. ### What does PEP 8 mean?

    PEP 8 is a document that provides guidelines and best practices on how to write Python code. The primary focus of PEP 8 is to improve the readability and consistency of Python code. [More details..](https://www.python.org/dev/peps/pep-0008/)

   **[⬆ Back to Top](#table-of-contents)**

## Core Python


3. ### First Class functions in Python?

    First class objects in a language are handled uniformly throughout. They may be stored in data structures, passed as arguments, or used in control structures. A programming language is said to support first-class functions if it treats functions as first-class objects. Python supports the concept of First Class functions.

    Properties of first class functions:
    * A function is an instance of the Object type.
    * You can store the function in a variable.
    * You can pass the function as a parameter to another function.
    * You can return the function from a function.
    * You can store them in data structures such as hash tables, lists… 
    
    [More details..](https://www.geeksforgeeks.org/first-class-functions-python/)
    
    **[⬆ Back to Top](#table-of-contents)**


4. ### Python Anonymous/Lambda Function?

    In Python, an anonymous function is a function that is defined without a name. While normal functions are defined using the def keyword in Python, anonymous functions are defined using the lambda keyword. Hence, anonymous functions are also called lambda functions. [More details..](https://www.programiz.com/python-programming/anonymous-function)

    ***Note:*** Lambda functions can have any number of arguments but only one expression. 
    
    **[⬆ Back to Top](#table-of-contents)**


5. ### Decorators in Python?

    A decorator is a design pattern in Python that allows a user to add new functionality to an existing object without modifying its structure. Decorators are usually called before the definition of a function you want to decorate. 
    
    [More details (Datacamp)...](https://www.datacamp.com/community/tutorials/decorators-python) | [More details (GeeksforGeeks)...](https://www.geeksforgeeks.org/decorators-in-python/)
    
    **[⬆ Back to Top](#table-of-contents)**


6. ### Generators in Python?

    Python generator functions are a special kind of function that return a lazy iterator. These are objects that you can loop over like a list. However, unlike lists, lazy iterators do not store their contents in memory. [More details...](https://realpython.com/introduction-to-python-generators/)
    
    **[⬆ Back to Top](#table-of-contents)**


7. ### Difference between == and is operator in Python?

    The Equality operator (==) compares the values of both the operands and checks for value equality. Whereas the ‘is’ operator checks whether both the operands refer to the same object or not. [More details...](https://www.geeksforgeeks.org/difference-operator-python/)
    
    **[⬆ Back to Top](#table-of-contents)**


8. ### Python Shallow Copy and Deep Copy?

    **Deep copy** is a process in which the copying process occurs recursively. It means first constructing a new collection object and then recursively populating it with copies of the child objects found in the original. In case of deep copy, a copy of object is copied in other object. It means that any changes made to a copy of object do not reflect in the original object. In python, this is implemented using “deepcopy()” function.

    A **shallow copy** means constructing a new collection object and then populating it with references to the child objects found in the original. The copying process does not recurse and therefore won’t create copies of the child objects themselves. In case of shallow copy, a reference of object is copied in other object. It means that any changes made to a copy of object do reflect in the original object. In python, this is implemented using “copy()” function.
    
    [More details...](https://www.geeksforgeeks.org/copy-python-deep-copy-shallow-copy/)
    
    **[⬆ Back to Top](#table-of-contents)**


9. ### Monkey Patching in Python (Dynamic Behavior)

    In Python, the term monkey patch refers to dynamic (or run-time) modifications of a class or module. In Python, we can actually change the behavior of code at run-time.
    
    [More details...](https://www.geeksforgeeks.org/monkey-patching-in-python-dynamic-behavior/)
    
    **[⬆ Back to Top](#table-of-contents)**


10. ### Context manager in python
    Context manager is used to set up and tear down resources, such as file handling or database connections, 
    in a clean and controlled manner.

    [More details...](https://www.geeksforgeeks.org/context-manager-in-python/)
    
    **[⬆ Back to Top](#table-of-contents)**