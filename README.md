# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
start the program
### Step 2: 
get the n values from the user
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
print the output
### Step 6: 
end the program
## Program:
```
#Program to circulate N values.
#Developed by:Gokul Prakash M
#RegisterNumber:23013924
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[ :n]
    print("After circulating the values are:",l)
```
## Output:
![Screenshot 2023-11-18 143005](https://github.com/gokulprakash23013924/Circulate-the-values-of-N-variables/assets/150231472/d8ef9ce0-a21e-4590-ab4c-3bb694894b79)


## Result:
thus the given program is successfully printed
