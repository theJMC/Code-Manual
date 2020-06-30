# Python Manual
(Python 3)

### Imports List

- GetPass - Easy get a password without the text being echoed 

  - Get Password: `getpass.getpass()`
  
- Columnar (Not in Standard Library - On pip) - Easy tables in Python

  - Create a Table: `table = columnar(data, headers)`
    - data = list - Data in the table 
    - headers = list - Strings of the Headers
  
- DateTime - Built In Date and Time module

  - Get the current time in the British Format: `datetime.now().strftime("%d-%m-%Y %H:%M")`

### Commands - Basic:

- `print(data)` - Prints out the variable data
- `variable = input()` - Asks the user to input something and stores it in the variable, variable
- If Statements:

### Commands - Variables:
- Defining an empty:
  - String: `variable = ""`
  - Integer: `variable = 0`
  - List: `variable = []`
  - Dictionary: `variable = {}`
- Casting to another type:
  - String: `str()`
  - Integer: `int()`
  - Unicode Number from Character: `ord()`
  - Character from Unicode Number: `chr()`
- #### Lists / Arrays:
  - Referencing a location in the list: `list[index_number]`
  - Adding to the end: `list.append(value_to_append)`
  - Remove something from the list:
    - Echo out and remove: `list.pop[index_number]`
    - Just remove an index: `del list[index_number]`
    - Remove the first matching index: `list.remove(string_to_remove)`
  - Inserting an item into the List: `list.insert(index, value)`


### Commands - Switch Style:

  -  `if [statement] [operator] [another statement]:` - start an if statement
  - `[statement]` - A variable or string that the command checks against
  - `[operator]` - The operation of comparison in the statement
    - `==` - Checks if something matches something else
    - `!=` - Checks if something does not match something else
    - `<` - Checks if something is smaller than something else
    - `>` - Checks if something is bigger than something else
  - You can also use boolean variables (`True` or `False`) in an if like this:
    - `if [boolean_variable]:` - It runs if the boolean is equal to `True`
  - Other statements in an if:
    - `elif` - Check for another condition after the first. Uses the same syntax as the input
    - `else` - The final path for an if statement, if all else fails, do this
- Try / Except Blocks:
  - `try:` - Place all of the code needed to be checked by the statement
  - `except [errorname] as [a variable]:` - If that code failed, do this
    - `[errorname]` - The name of the error your checking against, to take any error use `Error`.
    - `[A variable]` - A variable to store all of the information of the error. Particularly useful for error logs.

### Commands - Functions & Procedures:
- Defining a Function:
  - `def functionName(parameters):`
    - `[functionName]` - The names used when calling the function / procedure
    - `[parameters]` - The variable names used in the function 
  - Returning a variable after the function / procedure: `return [variable]`

### Commands - Classes:
- Defining a Class :
  - `class className:`
