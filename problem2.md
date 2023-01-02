### Task
You are given a string and your task is to swap cases. In other words, convert all lowercase letters to uppercase letters and vice versa.

### Solution
```python
def swap_case(s):
    newstring = ""
    for i in range(0,len(s)):
        if s[i] == s[i].upper() and s[i].isalpha():
            newstring = newstring+(s[i].lower())
        elif s[i] == s[i].lower() and s[i].isalpha() :
            newstring = newstring+(s[i].upper()) 
        else:
            newstring = newstring+ s[i]       
             
    return newstring
```
