# Exp.No:3c
## LIST - NUMBERS ENDING WITH 3 FROM A LIST

### AIM  
To write a Python Program to display the product of all the values which are ending with 3 from a list.

### ALGORITHM

1. Start
2. Input a list of integers and store it in variable l
3. Initialize a variable prod to 1 (to store the product)
4. Find the length of the list l and store it in variable x
5. Repeat for i from 0 to x - 1:
   - Check if the last digit of l[i] is 3 (i.e., l[i] % 10 == 3)
   - If true, multiply prod by l[i]
6. Print the final value of prod
7. End

### PROGRAM

```
# Reg.No-212223050048
# Name-SIBIRAJI M
# Write your code here
l=eval(input())
prod=1
x=len(l)
for i in range(0,x):
    if l[i]%10==3:
        prod*=l[i]
print("Product=",prod)
```

### OUTPUT

![image](https://github.com/user-attachments/assets/f0f753fb-52b9-46e4-b22a-573e34ca5f49)


### RESULT

Thus the Python Program to display the product of all the values which are ending with 3 from a list is executed successfully.



