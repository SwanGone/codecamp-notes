# CodeCamp Notes

Notes from the lectures


## NameError

This is an error produced when a object is referenced that does not exist or has no assigned value. This is generally caused by typos.

** Line 5 of uses the temp-celsuis variable when the correct variable is actually temp-celsius **

## ParseError

This error is produced when there is a syntaxical mistake which prevents the compiler from properly parsing the code.

** I forgot the close the parenthesis in the print argument on line 5 **

## TypeError

This error is caused by asking the code to manipulate a datatype that is inappropriate for the situation.

** Line 5 asks to mulitply the variable radius by pi but radius and string and not an integer or float **

## ValueError

This occurs when you pass a parameter to a function that can not use that particular parameter.

** For input the user entered ten as opposed 10 so line 5 can't turn the input into an integer. **

## AttributeError

This occurs when you try and call an attribute of an object that it does not possess.

** In line 5 the code calls to append the variable x to the variable myint but myint is not a list and does not possess the append attribute. **