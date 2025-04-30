# Exp.No:3d  
## TUPLES - A TUPLE WITH MULTIPLES OF 5

### AIM  
To write a Python program to create a tuple containing all multiples of 5 up to a given number **N**.

### ALGORITHM

1. Begin the program.  
2. Accept an integer `N` from the user.  
3. Use a generator expression inside the `tuple()` function to create a tuple `multiples_of_5` with values starting from `5` up to `N - 1`, stepping by `5`.  
4. Return the tuple `multiples_of_5`.  
5. Print the resulting tuple.  
6. Terminate the program.

### PROGRAM

```
# Reg.No-212223050048
# Name-SIBIRAJI M
# Write your code here
n=int(input())
tuple1=[]
for i in range(1,n):
    if i%5==0:
        tuple1.append(i)
print(tuple(tuple1))
```

### OUTPUT

![image](https://github.com/user-attachments/assets/a95a7cfc-f76a-4f4e-a67c-8064b196f0b7)

### RESULT

Thus the Python program to create a tuple containing all multiples of 5 up to a given number **N** is executed successfully.
