Python Basics:
Python: Python is a versatile, high-level programming language known for its simplicity and readability, suitable for various applications like web development, data analysis, and automation.

Key Features:

Simplicity: Clear syntax promotes readability and reduces development time.
Versatility: Used across industries for diverse tasks, from scripting to complex applications.
Rich Ecosystem: Extensive libraries (e.g., NumPy, Django) and active community support.
Installing Python:
Steps to Install Python:

Windows: Download installer from python.org, select "Add Python to PATH" during installation.
macOS: Install via Homebrew (brew install python).
Linux: Use package manager (sudo apt install python3 for Debian/Ubuntu).
Verify Installation:

Open terminal/command prompt and type python --version.
Set Up Virtual Environment:
Install virtualenv: pip install virtualenv.
Create and activate a virtual environment:

python -m venv myenv
source myenv/bin/activate  # macOS/Linux
myenv\Scripts\activate     # Windows
Python Syntax and Semantics:
# Hello, World! program
print("Hello, World!")
Basic Syntax Elements:
print(): Outputs text to the console.
"Hello, World!": String enclosed in double quotes.
Data Types and Variables:
Basic Data Types:

Integers (int), Floats (float), Strings (str), Booleans (bool)
Example Script:

# Variables and Data Types
num1 = 10
num2 = 3.14
name = "Alice"
is_active = True

# Operations
result = num1 + num2
print(result)  # Output: 13.14
Control Structures:
Conditional Statements and Loops:

If-Else Statement:
python
Copy code
# If-Else Statement
age = 18
if age >= 18:
    print("Adult")
else:
    print("Minor")
For Loop:
python
Copy code
# For Loop
for i in range(1, 5):
    print(i)
Functions in Python:
Functions: Reusable blocks of code for specific tasks.

# Function Example
def add_numbers(a, b):
    return a + b

# Function Call
sum_result = add_numbers(5, 3)
print(sum_result)  # Output: 8
Lists and Dictionaries:
Lists vs. Dictionaries:

Lists: Ordered collections accessed by index.
Dictionaries: Key-value pairs for unordered data.
Example Script:

# Lists and Dictionaries
numbers = [1, 2, 3, 4, 5]
person = {"name": "Bob", "age": 25}

# Operations
print(numbers[2])     # Accessing list element
print(person["name"]) # Accessing dictionary value
Exception Handling:
Exception Handling: Manages errors during program execution.

# Exception Handling
try:
    result = 10 / 0
except ZeroDivisionError as e:
    print("Error:", e)
finally:
    print("Completed")
Modules and Packages:
Modules and Packages: Encapsulate reusable code.

# Using Math Module
import math

# Example
print(math.sqrt(16))  # Output: 4.0
File I/O:
File Reading and Writing:

# Reading from a File
with open("myfile.txt", "r") as file:
    content = file.read()
    print(content)

# Writing to a File
data = ["apple", "banana", "cherry"]
with open("fruits.txt", "w") as file:
    for fruit in data:
        file.write(fruit + "\n")