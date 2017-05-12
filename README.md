# CodeCamp Notes

Notes from the lectures

# A function may have 0 or more parameters
    def add_two():
        return num + 2

# If you do not provide values for the parameters the function can't execute
def add_two(num):
    return num + 2

add_two()

TypeError: add_two() takes exactly 1 arguments (0 given) on line 4

# A function doesn't have to return a value but not doing so is kinda pointless
def add_two(num):
    num + 2

add_two(2)

# The value that is implicitly returned and stoed is the **special value** none
def add_two(num):
    result = num + 2

add_two(2)
print(result)

NameError: name 'result' is not defined on line 5

## NameError

This is an error produced when a object is referenced that does not exist or has no assigned value. This is generally caused by typos.

_Line 5 of uses the temp-celsuis variable when the correct variable is actually temp-celsius_

## ParseError

This error is produced when there is a syntaxical mistake which prevents the compiler from properly parsing the code.

_I forgot the close the parenthesis in the print argument on line 5_

## TypeError

This error is caused by asking the code to manipulate a datatype that is inappropriate for the situation.

_Line 5 asks to mulitply the variable radius by pi but radius and string and not an integer or float_

## ValueError

This occurs when you pass a parameter to a function that can not use that particular parameter.

_For input the user entered ten as opposed 10 so line 5 can't turn the input into an integer._

## AttributeError

This occurs when you try and call an attribute of an object that it does not possess.

_In line 5 the code calls to append the variable x to the variable myint but myint is not a list and does not possess the append attribute._