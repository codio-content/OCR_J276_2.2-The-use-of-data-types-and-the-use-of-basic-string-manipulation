String traversal means moving through a string, one character at a time. It can be used to see if it contains a particular character or group of characters.

```
sentence = “Computer Science.”
space = 0
for index = 0 to sentence.length – 1
  if sentence(index) == “ “ then
    space = space + 1
  endif
next index
print(space)
```
The print statement would return the number 1 as there is only one space in the sentence.