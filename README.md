# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Define a function.

### Step 2: 
Get the list from the user.

### Step 3: 
Get the value from the user for the number of rotation

### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Print the list.

### Step 6: 
End the program

## Program:
~~~
#Program to Circulate the n variables using function concept
#Developed by: MOHAMED HAMEEM SAJITH J
#Reg num: 21223240090
def circulate():
    a=eval(input())
    b=int(input())
    for i in range(b):
        temp=a.pop(0)
        a.append(temp)
    print("After circulating the values are:",a)
~~~
## Output:
![image](https://github.com/Sajith7862/Circulate-the-values-of-N-variables/assets/145972360/c2141510-ea5c-4a69-accb-e6d102fc8732)

## Result:
Thus the program to circulate the n variables using function is written and verified using python programming.
