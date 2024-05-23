# Library Installation and Importing


### Intro
Now that you know the basics of syntax, I'll introduce the core of Python's functionality, Libraries!

### Lesson Two
### Syntax
Python's import syntax, is, as usual, amazingly simple, with only a few keystrokes you can gain access to a vast quantity of functions and utilities.

##### Library Installation
Included with your Python installation came a command line tool called **pip**. **Pip** stands for "pip Install Packages" and helps to install libraries for use within your Python project. These packages are installed from a collection called Pypi, packages and their descriptions can be found on Pypi's website. ([Pypi.org](https://pypi.org/))
Pip can be utilized for installation using the terminal on your computer, you can simply type:
```Bash
pip install <LIBRARY_NAME>
```
Some Python projects you may find online (And all included with this program) will include a `requirements.txt` file, this file contains information pip uses to install the correct packages for the functions within the project to run properly. To utilize this file, simply locate where your requirements file is on your computer, and run a simple command:
```Bash
pip install -r <PATH_TO_REQUIREMENTS/requirements.txt>
```

##### Importing
When importing a Python library you have a few options, a Python library is typically a collection of functions, you can choose to import the entire library including all the functions within, or you can choose specific functions to import:
1. Importing the entire Library and all of the included functionality
```Python
import math
```
2. Importing only a specific function (In this case the function for square rooting)  
Now when we call the function from the math library, we use `sqrt()` without `math.` included in the call, however this also means that we now only have access to the `sqrt` function from the math library
```Python
from math import sqrt 
```
3. Importing the library under a different label  
This means that instead of using a function like this: `math.sqrt()`, you now call is like this: `mt.sqrt()`
```Python
import math as mt 
```
4. Combining the label and specific function
```Python
from math import sqrt as st 
```
##### Open-Ended Question
###### Directions:
Write a function that takes in `a`, `b`, and `c` values and preforms quadratic formula and returns the y-intercepts of the function  
Quadratic formula can be found here [Formula](https://en.wikipedia.org/wiki/Quadratic_formula)