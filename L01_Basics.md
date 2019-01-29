# Python Tutorial for Machine Learning I

## Introduction

From the official Python docs:

> Python is an easy to learn, powerful programming language. It has efficient high-level data structures and a simple but effective approach to object-oriented programming. Python’s elegant syntax and dynamic typing, together with its interpreted nature, make it an ideal language for scripting and rapid application development in many areas on most platforms.

These are the reasons why we and many machine learning researchers have chosen Python for machine learning.

We will very losely follow the official Python 3.7 tutorial which is available [here](https://docs.python.org/3/tutorial/index.html). This document, however, will only contain/link to the parts of the language that we explicitly discuss in class.

Python is a well-documented language. Everything you need to know about the core language is in the official [docs](https://docs.python.org/3), and everything you need to know about the few libraries we will actively use can be found in their respective docs.

## Comments

`# This is a comment. It starts with a hash sign`. A comment will not be executed, even if it contains executable code.

## Imports

Python is a modular language. This means most of the useful extensions of the language will come as libraries that you will need to install and import. Fortunately, as we are using the Anaconda distribution and are working inside an environment, this is easy. Simply install the respective package in your environment and then run ìmport package`. For packages that are used really frequently in the code, you can also change the name to something shorter with the às` keyword, for instance: ìmport torchvision as tv`. You can also import only parts of a package with the `from` keyword.

## Variables

While the technical reality is a bit more complicated, we can regard variables as *signs that holds values*. In Python, we can assign a value to a sign with the equality operator: `a = 1`. Variables can hold many different kinds of values, integers (`a = 1`), floating point numbers (`a = 1.5`), characters (`a = 'a'`), words (`a = 'foo'`), truth values (`True`or `False`) vectors, matrices, or even complicated structures made up of many different kinds of values, called objects. Python is a [weakly-typed](https://en.wikipedia.org/wiki/Type_system) language. In practice, this means that we do not have to tell the interpreter what kind of value we are assigning to a sign, it will infer this for us.

There are many different way to "look into" a variable, i.e. see what value it is holding at a certain point in the execution of the program. A very easy way is to just print its value to the console/notebook. In Python, we use the `print` function for this purpose: `print(a)`.

As variables can hold values, we can use them algebraically, almost exactly like we would without a computer. For instance, we could calculate the sum of `a=4`and `b=2` by assigning it to `c`: `c=a+b`. `print`ing `c` will give us the result: `6`. Many other algebraic operations are possible:

- `print(a-b)`: 2
- `print(a*b)`: 8
- `print(a**b)`: 16, power
- `print(a/b)`: 2
- `print(a//b)`: 2, floor division

We can also obtain truth values from algebraic statements using variables. For instance, to check for equality, we use the `==`operator:

- `print(a==b)`: False
- `print(a>b)`: True
- `print(a<b)`: False
- `print(a>=b)`: True
- `print(a<=b)`: False

## Next

In the next few meetings, we will talk about:

- Flow control
- Functions
- Lists and dictionaries
- Numpy
- PyTorch