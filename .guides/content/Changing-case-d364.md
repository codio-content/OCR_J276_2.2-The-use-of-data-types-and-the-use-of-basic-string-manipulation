Often the string may need to be changed into upper or lower case.
This may be when checking user input. If they have been asked to enter ‘A’ the if the entry is changed to upper case their entry will be acceptable if they have entered ‘a’.

Changing the case to upper and lower case could be done in the following way:
```
entry = input(“Please enter ‘X’ to exit the game.”)
entryUpperCase  = entry.upper
entryLowerCase = entry.lower
```