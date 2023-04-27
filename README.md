# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Take input from the user.
### Step 2: 
Use functions and pass parameters.
### Step 3: 
Get the value from the user for the number of rotation.
### Step 4: 
Using the slicing concept rotate the list.
### Step 5: 
print circulated values.
### Step 6: 
End the program.
## Program:
```
#Program to circulate N values.
#Developed by: Thivakar.R
#RegisterNumber:212222240109
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
```
## Output:
![Screenshot 2023-04-27 142313](https://user-images.githubusercontent.com/118707074/234812536-93a3ab28-c302-4d25-9e07-7a9d609d0344.png)



## Result:
Thus the circulate the n variables using function is successfully executed.
