# Whta is Python ?
* Pyhon is a simple and easy to understand language which feels like reading simple english. This Pseudo code nature of python makes. it wasy to learn and understandable bny biginners.

## Feature of python
* Easy to understnad = less development time 
* Free and open source
* High level language
* Portable -> Work on linux / windows / mac.


##############################

# CHAPTER 1 :- Modules, Comments & Pip
## lets write our very first python program

````
print("Hello World)
````
# Modules :->
* A module is a file containing code written by somebody else(usually) which can be imported and used in our programs

## Types of modules
* Built in modules 
* External modules

## Using python as a calcutor
* We can use python as a calculator by typing "Python + on the terminal

# Comments :->
*   Comments are used to write something which the programmier does not want to execute.
          *  Types of comments
1 Single line comments -> #
2 Multi line commnets -> Writtern using ''' comment'''

# Pip :->
* Pipe is the package manger for python you can use pip to install a module on your system


# CHAPTER - 2 VARIABLES AND DATATYPES

* A variable is the name given to a memory location in a program for example

    *  primarly there are following data types in python
    1) Integers
    2) Floating point numbers
    3) Strings
    4) Booleans
    5) None

    a = 71
    b = 88.44
    name = "Jitu raj sharma"

    * A variable name can contain alphabets, digits and underscors
    * A variable name can only start with an alphabet and underscore
    * A variable name can't start with a digit a variable name.

    # Operators in python
    * Arithmetic operators = + - * /
    * Assignment operators = =+ = -= 
    * Comparison operators = ==, > >= < , !
    * Logical operators = and, or, not

# type() function and Typecasting
* type function is used to find the data type of a given variable in python

````
    a = 31
    type(a) => class <int>
    b = "31"
    type(b)  => class <str>

````
* A number can be converted into a string and vice versa (if possible)
* There are many functions to converted one data type into another

str(31) ="31"  -> Integer to string conversion
int('32') = 32   -> String to integer conversion
float(32) = 32.0  -> Integer to float conversion


# ...and so on
*  Here "32" is a string literal and 31 a number literal


# intput() function 
* This function allows the user to take input from the keyboard as a string

````
a = input("Enter name") 
````
* It is  imported to note that the output of input is always a string(even if the number is entered)

