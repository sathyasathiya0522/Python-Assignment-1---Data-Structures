Python Assignment 1 - Data Structures: Strings & Tuples

Project Overview

This beginner-level Python assignment demonstrates fundamental operations on strings and tuples. It covers user input, concatenation, indexing, slicing, built-in string methods, tuple creation, concatenation, repetition, and element access.

Objectives

Accept and display user input

Combine strings using concatenation

Access and extract characters using indexing and slicing

Reverse a string using slicing

Apply common string methods

Create and manipulate tuples

Understand that tuples are immutable

Technologies Used

Python 3

Google Colab

Assignment Tasks

1. String Concatenation

The program accepts the user's name and combines it with greeting messages.

name = input("Enter your Name: ")

string1 = "Hello"
combined_string = string1 + " " + name
print(combined_string)

string3 = "welcome to Python programming"
final_string = combined_string + ", " + string3
print(final_string)

Sample output:

Enter your Name: Subramaniyam
Hello Subramaniyam
Hello Subramaniyam, welcome to Python programming

2. String Slicing and Indexing

The concatenated string is used to access the first and last characters, extract selected portions, reverse the string, and extract the word Python.

print("First character:", final_string[0])
print("Last character:", final_string[-1])
print("First 5 characters:", final_string[:5])
print("Last 11 characters:", final_string[-11:])
print("Reversed string:", final_string[::-1])

python_start = final_string.index("Python")
print("Extracted word:", final_string[python_start:python_start + 6])

Sample output:

First character: H
Last character: g
First 5 characters: Hello
Last 11 characters: programming
Reversed string: gnimmargorp nohtyP ot emoclew ,mayinamarbuS olleH
Extracted word: Python

3. String Methods

The program applies upper(), lower(), capitalize(), count(), and replace() to a string.

strM = "Python beginner tutorial"

print("Uppercase:", strM.upper())
print("Lowercase:", strM.lower())
print("Capitalized:", strM.capitalize())
print("Number of 't':", strM.count("t"))
print("Replaced string:", strM.replace("Python", "Data Analytics"))

Sample output:

Uppercase: PYTHON BEGINNER TUTORIAL
Lowercase: python beginner tutorial
Capitalized: Python beginner tutorial
Number of 't': 3
Replaced string: Data Analytics beginner tutorial

4. Tuple Operations

Two tuples are created and used to demonstrate concatenation, repetition, indexing, and slicing.

tuple1 = (10, 20, 30)
tuple2 = (40, 50, 60)

t_combine = tuple1 + tuple2
repeated_tuple = t_combine * 3

print("Combined tuple:", t_combine)
print("Repeated tuple:", repeated_tuple)
print("Third element:", t_combine[2])
print("First three elements:", t_combine[:3])
print("Last three elements:", t_combine[-3:])

Sample output:

Combined tuple: (10, 20, 30, 40, 50, 60)
Repeated tuple: (10, 20, 30, 40, 50, 60, 10, 20, 30, 40, 50, 60, 10, 20, 30, 40, 50, 60)
Third element: 30
First three elements: (10, 20, 30)
Last three elements: (40, 50, 60)

Key Concepts Learned

Python uses zero-based indexing, so the third element is accessed with index 2.

A negative index accesses elements from the end of a sequence.

Slicing uses the format start:stop:step.

The slice [::-1] reverses a string or tuple.

String methods return modified strings without changing the original string.

Tuples are ordered but immutable, meaning their elements cannot be changed after creation.

Repository Contents

Python-Assignment-1-Strings-and-Tuples/
|-- Python_Assignment_1_Strings_and_Tuples.ipynb
`-- README.md

How to Run

Open Python_Assignment_1_Strings_and_Tuples.ipynb in Google Colab or Jupyter Notebook.

Run each cell in sequence.

Enter a name when prompted.

Review the output displayed below each cell.

Author

Subramaniyam R
Aspiring Data Analyst
