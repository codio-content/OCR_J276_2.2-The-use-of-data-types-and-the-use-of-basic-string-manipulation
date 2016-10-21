Numeric data within a string may be needed for a mathematical calculation and must therefore be converted from string data type to a mathematical one, such as an integer or a real number.
```
string = “3”
number = int(string)
numberReal = float(string)    //This should be used for numbers with decimal places.
To convert an integer into a string:
number = 3
string = str(number)
```
