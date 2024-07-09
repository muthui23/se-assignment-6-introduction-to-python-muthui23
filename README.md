[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15389704&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.
   Python is a high-level, interpreted programming language known for its simplicity and readability. It supports multiple programming paradigms, including procedural, object-oriented, and functional programming.
   It is used in web development, data analysis, artificial intelligence, scientific computing, and automation.
   Key features.
   1.Readability
   2.Versatility
   3.Extensive Libraries

2. Installing Python:
   Steps to Install Python:
Download Python:
Visit the official Python website: python.org.
Download the latest version of Python for your operating system.
Install Python:
Run the installer and follow the prompts. Make sure to check the "Add Python to PATH" option.
Open a terminal or command prompt and type:
python --version
Create a virtual environment
python -m venv myenv

3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.
print("Hello, World!")

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.
int: Integer values.
float: Floating-point numbers.
str: Strings or text.
bool: Boolean values (True or False).
list: Ordered, mutable collections.
dict: Key-value pairs, unordered.
 
 script:
 # Integer
x = 10
print(type(x), x)

# Float
y = 3.14
print(type(y), y)

# String
z = "Hello"
print(type(z), z)

# Boolean
a = True
print(type(a), a)

# List
b = [1, 2, 3]
print(type(b), b)

# Dictionary
c = {"key": "value"}
print(type(c), c)

5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.
control structures are used to control the flow of execution in a program. The two main types of control structures are conditional statements and loops.
if-else
age = 18

if age >= 18:
    print("You are an adult.")
else:
    print("You are a minor.")
Loops in Python allow you to repeatedly execute a block of code until a certain condition is met.
for loop
fruits = ["apple", "banana", "cherry"]

for fruit in fruits:
    print(fruit)

6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.
Why Functions are Useful:
Code Reusability
Modularity: Functions help in organizing code into smaller, manageable sections.
Abstraction
7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.
Lists: Ordered collections, indexed by position.
Dictionaries: Unordered collections, indexed by keys.
 
 script
 # Lists
numbers_list = [1, 2, 3, 4, 5]
print("List of numbers:", numbers_list)

# Accessing elements in a list
print("First element in the list:", numbers_list[0])
print("Last element in the list:", numbers_list[-1])

# Modifying an element in the list
numbers_list[2] = 10
print("Modified list:", numbers_list)

# Adding an element to the list
numbers_list.append(6)
print("List with added element:", numbers_list)

# Dictionaries
person_dict = {
    "name": "John Doe",
    "age": 35,
    "occupation": "Software Engineer"
}
print("\nDictionary of person information:", person_dict)

# Accessing values in a dictionary
print("Name:", person_dict["name"])
print("Age:", person_dict["age"])

# Adding a new key-value pair to the dictionary
person_dict["email"] = "john.doe@example.com"
print("Dictionary with added key-value pair:", person_dict)

# Modifying a value in the dictionary
person_dict["age"] = 36
print("Dictionary with modified value:", person_dict)


8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.
Exception handling in Python is a mechanism that allows you to handle and manage unexpected or exceptional situations that may occur during the execution of a program.

example
def divide_numbers(a, b):
    try:
        result = a / b
        print(f"The result of {a} / {b} is: {result}")
    except ZeroDivisionError:
        print("Error: Division by zero is not allowed.")
    except TypeError:
        print("Error: Both arguments must be numbers.")
    finally:
        print("The division operation has completed.")


divide_numbers(10, 2)  # Output: The result of 10 / 2 is: 5.0, The division operation has completed.
divide_numbers(10, 0)  # Output: Error: Division by zero is not allowed., The division operation has completed.
divide_numbers(10, "2")  # Output: Error: Both arguments must be numbers., The division operation has completed.

9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.
   Modules and Packages:
Module: A file containing Python definitions and statements.
Package: A collection of modules in directories that give a package hierarchy.

script
import math

# Using math module
result = math.sqrt(16)
print(result)


10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.
    reading from a file
    with open('example.txt', 'r') as file:
    content = file.read()
    print(content)

writing to a file
lines = ["First line\n", "Second line\n", "Third line\n"]
with open('output.txt', 'w') as file:
    file.writelines(lines)



# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


