# Exp.No:3a
## STRING - FIND AND REPLACE

### AIM  
To write a Python function to accept a string, identify a word to be replaced, and replace it with a new word provided by the user.

### ALGORITHM

1. Begin the program.  
2. Input the original string `str1` and the word to be replaced `replace_str`.  
3. Ask the user to input the new replacement word `str2`.  
4. Use the `replace()` method in Python to replace all occurrences of `replace_str` in `str1` with `str2`.  
5. Store the modified string in `str3`.  
6. Display the original string (`str1`) and the modified string (`str3`).  
7. Terminate the program.

### PROGRAM

```
# Reg.No-212223050048
# Name-SIBIRAJI M
# Write your code here
def replacestr(a,b):
    val = input()
    print("The old string is",a)
    c  = a.split()
    if val !=  "burger":
        print("the new string is",val,c[1])
    else:
        print("the new string is",c[0],val)

```

### OUTPUT

![image](https://github.com/user-attachments/assets/ab464c6c-b49a-47d2-afd0-3aebb95a5071)

### RESULT

Thus the Python function to accept a string, identify a word to be replaced, and replace it with a new word provided by the user is executed successfully.
