
0x00. Python - Variable Annotations
Overview
This project is part of the alx-backend-python repository and focuses on understanding and utilizing type annotations in Python. The project covers various aspects of type annotations, including function signatures, variable types, and duck typing. It also emphasizes the use of mypy for validating code.

Learning Objectives
By the end of this project, you will be able to:

Understand and apply type annotations in Python 3
Specify function signatures and variable types using type annotations
Explain the concept of duck typing
Validate Python code using mypy

Requirements
Allowed editors: vi, vim, emacs
Python version: python3 (version 3.7)
Files should end with a new line
The first line of all files should be #!/usr/bin/env python3
Code should follow the pycodestyle style (version 2.5)
Files must be executable
Modules, classes, and functions should have documentation

Tasks
0. Basic annotations - add
Write a type-annotated function add that takes two floats a and b and returns their sum as a float.

File: 0-add.py

1. Basic annotations - concat
Write a type-annotated function concat that takes two strings str1 and str2 and returns their concatenated string.

File: 1-concat.py

2. Basic annotations - floor
Write a type-annotated function floor that takes a float n and returns the floor of the float.

File: 2-floor.py

3. Basic annotations - to string
Write a type-annotated function to_str that takes a float n and returns the string representation of the float.

File: 3-to_str.py

4. Define variables
Define and annotate the following variables with the specified values:

a: an integer with a value of 1
pi: a float with a value of 3.14
i_understand_annotations: a boolean with a value of True
school: a string with a value of "Holberton"
File: 4-define_variables.py

5. Complex types - list of floats
Write a type-annotated function sum_list that takes a list of floats and returns their sum as a float.

File: 5-sum_list.py

6. Complex types - mixed list
Write a type-annotated function sum_mixed_list that takes a list of integers and floats and returns their sum as a float.

File: 6-sum_mixed_list.py

7. Complex types - string and int/float to tuple
Write a type-annotated function to_kv that takes a string k and an int or float v and returns a tuple. The first element of the tuple is the string k, and the second element is the square of the int/float v as a float.

File: 7-to_kv.py

8. Complex types - functions
Write a type-annotated function make_multiplier that takes a float multiplier and returns a function that multiplies a float by multiplier.

File: 8-make_multiplier.py

9. Let's duck type an iterable object
Annotate the function element_length with appropriate types.

File: 9-element_length.py

10. Duck typing - first element of a sequence
Augment the function safe_first_element with correct duck-typed annotations.

File: 100-safe_first_element.py

11. More involved type annotations
Add type annotations to the function safely_get_value.

File: 101-safely_get_value.py

12. Type Checking
Use mypy to validate the code in 102-type_checking.py and apply any necessary changes.

File: 102-type_checking.py

Resources
Python 3 typing documentation
MyPy cheat sheet

Usage
Clone the repository:

git clone git@github.com:admens2008/alx-backend-python.git

Navigate to the project directory:

cd alx-backend-python/0x00-python_variable_annotations

Run the Python scripts according to the tasks.
