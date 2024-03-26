VARIABLES AND SCOPE

Local Scope: Variables defined within a function have local scope, meaning they can only be accessed within that function.
python
def my_function():
    x = 10  # local variable
    print(x)

my_function()  # Output: 10
print(x)  # Error: NameError: name 'x' is not defined
Global Scope: Variables defined outside of any function have global scope, meaning they can be accessed anywhere in the code.
python
x = 10  # global variable

def my_function():
    print(x)

my_function()  # Output: 10
print(x)  # Output: 10
Enclosing Scope (Nonlocal Variables): In nested functions, variables can be accessed from the enclosing (outer) scope using the nonlocal keyword.
python
def outer_function():
    x = 10  # outer function's variable

    def inner_function():
        nonlocal x
        x += 5  # accessing and modifying outer function's variable
        print(x)

    inner_function()  # Output: 15

outer_function()
Built-in Scope: Python provides several built-in functions and constants which are always accessible from any scope without the need for an import statement. Examples include print(), len(), range(), etc.
python
print(len([1, 2, 3]))  # Output: 3
Scope Resolution: When a variable is referenced, Python searches for it in the local scope first, then in the enclosing scope (if any), then in the global scope, and finally in the built-in scope. If the variable is not found in any of these scopes, a NameError is raised.
python
x = 10

def my_function():
    x = 20  # this is a different variable 'x' local to the function
    print(x)  # Output: 20

my_function()
print(x)  # Output: 10

VARIABLES AND FUNCTIONS

A variable is essentially a place where we can store the value of something for processing later on. Imagine you wanted to write a program that doubled a number for us, not the most exciting of programs I know but it is a good example.

We would first want to define a variable to store our number, double it and then print it out.

Open up visual studio code and create a new python file called double.py. In this double.py file you will want to add the following code:

my_number = 2
print(my_number)

my_number = my_number * 2
print(my_number)
We start off by defining a new variable called my_number and setting this new variable to equal 2. After this we then print out the value of our variable using the print function and passing in what we wish to print, in this case we wish to print our my_number variable.

When you run this you should see the number 2 being printed out in the console.

     my_number = 2
     print(my_number)
     2
After this we then re-assign our my_number variable to equal the current value of my_number times 2. This doubles our starting number. When we now run this program you should see the number 4 being printed out below our 2 value.

     my_number = 2
     print(my_number)
     2
     my_number = my_number * 2
     print(my_number)
     4

FUNCTIONS

imagine you had a maths program that could either double or triple a number of your choice. You would want to define two distinct functions that would take in a number and either double or triple it.

In order to define functions in python we can use the def keyword followed by the name of the function we wish to define like so:

def double(my_number):
This is known as a function declaration and it’s below this function declaration that we’ll define what we want our function to do. You should notice that we’ve included (my_number) beside our function, this is how we define what goes into every function. In this case we want it to take in a my_number variable which we will then go on to double within our function.

def double(my_number):
    return my_number * 2
If we then wished to use this function then we could do something like this:

def double(my_number):
    return my_number * 2

     create a new variable called `my_var` which equals
     the value returned by calling double() on the value 5.
     my_var = double(5)
     print our new `my_var`
     print(my_var)
