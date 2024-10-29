# Python
python Basics:
it is a beginner-friendly programming language that is used in web development.
this programming language is known of its easy to read syntax and of its capabilities. 
To install packages on Python make use of "pip install" 
To verifie a version "python --version"
To run a script "python your file name.py"
To add comment #

Python Variables:
Refers to a name that refers to a value stored in the computers memory. Variable allow you to store, manipulate, & retrieve data within your programs.
Use descriptive names for your variables to make your code more readable and maintainable
Declaring Variables:
You will simply assign a value to a variable using the = operator. 

Basic Data types:
integers (int)
age = "30"
float-point numbers (float)
height = "5.9"
strings (str)
name = "Alice"
boolean values (bool)
To control flow of your program:
Conditional statements (if, else, elif) 
Loops (for, while)

Compound Data Types:
list (list)
Alphabets  = ["A", "B", "C"]
Tuple (tuple)
coordinates = (10.1, 20.0)
Dictionary (dict)
person = {"name": "Asiphe", "Age": 24}
Set (set)
unique_numbers = {1, 2, 3}

Type Conversion:
Be consistent with your 
Implicit Type Conversion
result = 10 + 3.5
Explicit Type Conversion
num_str = "100" # converts string to integer.

To check data type:

print(typ(age)) # output: <class 'int'>

Operators & Expressions:
Operators refer to special symbols or keywords that perform operations on python variables and values. 
Expressions:
Refers to a combination of values, variables and operators that Python interprets and evaluate to produce results.
Types of Operators: 
Arithmetic Operators: Addition (+), Substraction (-), Multiplication (*), Division (/), Floor division (//), Modulus (%) & Expontiation (**).
Comparison Operators: Equal (==), Not Equal (!=), Greater Than (>), Less Than (<), Greater Than or Equal To (>=)& less Than or Equal To (<=).
Logical Operators: AND (and), OR (or) & NOT (not).
Assignment Operators:  Equal (=), Add and Assign (+ =), Multiply and Assign (*=) & Divide and  Assign (/=).
Identity Operators: Is (is) & Is Not (is not).
Membership Operators: In (in) & Not In (not in).
Bitwise Operators: AND (&) , OR (|), XOR (^), NOT (~), Left Shift (<<) & Right Shift (>>).

Control structures (if-else, loops)
if-else and loops are primary control structures that allow you to dictate the flow of your program.

1. Conditional statement (if-else):
Allow you to execute certain blocks of code based on specific conditions. 
Syntax involves using if, elif (short for "else if"), and else to evaluate expressions and decide which code to run.

If Statement: Executes a block of code if the condition is true.
Elif Statement: Checks another condition if the previous conditions were false.
Else Statement: Executes a block of code if all previous conditions were false.

2. Loops:
They allow you to repeat a block of code multiple times. 
Two types of Loops:
For Loops: Involves lists, tuple, or strings.
Most used over a sequence & executes a block of code for each item in the sequence.
While Loops: Can be used to repeat a block of code as long as a condition is true.

3. Combining if-else with Loops
   you willcombine conditional statements with loops to control how many times a loop runs or to break out of a loop early.

4. Best Practices:
   Identation
   Clear Conditions
   Avoid Infinite Loops

Functions & Modules:
These concepts help you to organize, reuse & manage your code efficiently. 

1. Function:
Refers to blocks of reuseable code that perfom a specific task.
Functions allow you to breake down your code into smaller, manageable pieces.
You define a function by using the def keyword, followed by the function word. inside the function yu write the code that you want to execute when the function is called.
2. Modules:
Are files that contain Python code, which can include functions, variables & classes.
Your modules should be saved in a .py file.
To import a module in your program, you must import it using the import keyword.

Lists, tuples, dictionaries, sets:
These are Python data structures that are essential for organizing and managing data.
1. Lists:
   It is an ordered collection of items that can hold a variety of data types (integers, strings, other lists)
   CHARACTERISTICS:
   Order: have order and indexed
   Mutability: can be modified by add, removing or changing elements
   Heterogeneous: they can contain different types of data.

Common Operations: 
Adding Items: uses append() to add an item to the end of a list, insert () to add at a specific position
Accessing Items: Use indexing (list[0] for the first item or slicing for a sublist [1:3]
Remving Items: use remove() to remove a specific item or pop() to remove an item at a specific index.
Looping Through Lists: Uses for loop to iterate through each item in the list

2. Tuples:
   Refers to an order of collection of items similar to a list but unlike lists, tuples are immutable. onces created they cannot be changed.
   CHARACTERISTICS:
   Order: are ordered & indexed 
   Immutable: cannot be modified
   Heterogeneous: they can contain different types of data.

Common Operations:
Accessing Items: similar to lists, allow you to use indexing & slicing
Tuple Unpacking: Assign elements of a tuple to multiple variables in one step
Creating Single-Element Tuples: usea comma after the single element (my_tuple = (5,)).

3. Dictionaries:
   It is collection of key-value pairs where each key is unique. Dictionaries are mutable, allowing you to change, add, or remove key-value pairs. 
