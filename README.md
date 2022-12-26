# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Import def circulate.
### Step 2: 
Prepare the lists from each linear equations and assign in np.array().
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Add coding to the input value.
### Step 6: 
Add coding to the input value.
## Program:
 ```python
#Program to circulate N values.
#Developed by: sudhakar 
#RegisterNumber: 22007876
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)

 ```
## Output:
![output](./output.png)

## Result:
thus circulating the values of N variables using python program successfully executed
