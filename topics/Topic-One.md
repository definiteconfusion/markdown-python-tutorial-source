# Basic Datatypes, Operators, and Structures


### Intro
Welcome to Python, an open source interoperated programming language. (Don't worry if you don't know what that mean) Python uses clear and simple syntax to complete complex tasks across various platforms and in many environments, from deep learning to web servers Python can pretty much do anything. 

### Lesson One
##### Introduction
First things first, lets learn a little about how Python works, Python works through manipulating data through operators, through the next few subsections, we will explore the basic datatypes, operators, and structure.

##### Basic Datatypes
In Python, (And most other programming languages) there are differing types of data, in Python there include: 
1. `str` - String: Represent the literal characters in the string, for instance `"3"` is not a number, it is a character, so `"3" + "3"` would equal `33` not `6`. (The `+` operand is called "concatenation" when combining strings)
2. `int` - Integer: Represents a number without a decimal point, unlike with a numerical within a string, integers can have mathematical operators applied
3. `float` - Float: Represents a number that contains a decimal point, the number to the right of the decimal point can be zero, for example, `1.0`(a float) is different to `1`(an integer), although both are valid can have mathematical operators applied
4. `list` - List: Represents a list of other values, values can be any datatype including another list, lists are structured with comma separated values book-ended by square brackets, an example being: `["Foo", "Bar"]`
5. `tuple` - Tuple: Represents data very similarly to a list, but with some key differences in terms of data creation, for instance give a variable the values held in multiple other variables, the value of the new variable will be of type tuple, `variableOne, VariableTwo, VariableThree = mainVariable` (Main variable will be a tuple). Tuples also have some syntactic differences to a list, instead of square brackets book-ending as in a list, in a tuple we use parenthesis: `("Foo", "Bar")`
6. `dict` - Dictionary: Represents labeled data, each index of the dictionary will have a "key", this key is the data's label, this is useful for retrieving data that may not necessarily be in a specific order, this data is structured as such: `{"key": "data", "anotherKey": "moreData"}`
7. `bool` - Boolean: Represents the truth of a statement, there are only two options, `True` or `False`, so for instance if I declare `isEqual = (1 == 2)`, then `isEqual` will hold the value `False` because one and two are not equal values

##### Basic Math Operators
Just as with datatypes, Python possesses differing type of "operators" that can be applied to the above data types, these include:
1. `+` - Addition / Concatenation: This operator allows the values two objects to be combined, for types `int` and `float`, values are mathematically added(Addition), for type `str`, values are combined (Concatenation)
2. `-` - Subtraction: This operator allows for a value to be subtracted from another value 
3. `*` - Multiplication: This operator allows for `int` and `float` objects to be mathematically multiplied, and a `int` / `float` values to determine the number of times a `str` objects is to be repeated
4. `/` - Division: This operator allows for an `int` / `float` object to be divided by another `int` / `float` object
5. `//` - Floor: This operator returns the number of times that the divided value can fit within the first value, for example: `9 / 2 -> 4.5`, but `9 // 2 -> 4` 
6. `%` - Modulo: This operator preforms a floor operation and reflects the remainder 

##### Basic Structures
Python uses certain logical structures that organize, and stack operators to further parse data, these include:
1. Functions: This structure represents a chuck of cde within a separate "scope" that is named for later use and reuse, values are assumed to exist and can be used within the function and values from within the function can be passed back out of the function, then when the function is called (used), those assumed objects are given values from other data so that the operators within the function can be applied to the real data
2. Loops: This structure allows for the script set within the loop to be repeated, this repeat can be constrained to a set number of times, or it can repeat until a condition is met.
3. Conditionals: This structure allows for a chunk of code to be executed conditionally, this means that only if a condition is met, `if 1 == 1:`, will the code within the statement's scope be executed.
4. Try Statements: This structure allows for the interpreter to "try" a chunk of code, if the interpreter encounters and error, there must be a backup "except" statement to execute without triggering an error

##### Practice Problems
###### PP1 - Directions:    
Print the phrase `Hello World` ten times  
###### PP1 - Answer: 
```Python
for i in range(10):
    print("Hello World")
```
###### PP2 - Directions:
Create a function that takes two inputs, `firstName` and `secondName`, then prints `Hello {firstName}, isn't Python awesome. -{secondName}`
###### PP2 - Answer:
```Python
def prinLetter(firstName, secondName)
    print(f"Hello {firstName}, isn't Python awesome. -{secondName}")
```

##### Open-Ended Question
###### Directions:
Create a function that takes in one input, `word`, then, print the word one more time per loop for 10 run-throughs