# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
### Step 2: 
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Use print function to display output

## Program:
~~~
#Program to circulate N values.
#Developed by   :  Venkatesh E
#RegisterNumber :  21003352
def circulate():
    num=[10,20,30,40,50,60]
    n=int(input())
    c=num[n:]+num[:n]
    print ("After circulating the values are:",c)
    return c
~~~
## Output:
![GitHub Logo](Capture.jpg)

## Result:
Thus using slicing operator we circulate the value.