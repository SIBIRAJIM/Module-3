# Exp.No:3e
## SEB - STRING SLICING

### AIM  
To write a Python function  to find sequences of Lower case letters joined with a '@'.

### ALGORITHM

1. Start
2. Input a string and store it in variable a
3. Use a regular expression pattern "[a-z]+@" to search within a:
    - The pattern matches one or more lowercase letters followed by @
4. If a match is found:
    - Print "Found a match!"
5. Else:
    - Print "Not matched!"
6. End

### PROGRAM

```
# Reg.No-212223050048
# Name-SIBIRAJI M
# Write your code here
import re
a= input()
matched=re.search("[a-z]+@",a)
if matched:
    print("Found a match!")
else:
    print("Not matched!")
```

### OUTPUT

![image](https://github.com/user-attachments/assets/2cbfe02f-f9b2-4f0f-a86d-594150d1e3bf)


### RESULT

Thus the Python function  to find sequences of Lower case letters joined with a '@' is executed successfully.
