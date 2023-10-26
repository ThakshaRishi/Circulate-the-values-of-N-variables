# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
Define a method 'circulate'
### Step 2: 
Get the list values from the user
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print the circulated list
### Step 6: 
End the program
## Program:
```
#Program to circulate N values.
#Developed by: Thaksha Rishi
#RegisterNumber:23013212
def circulate():
    l=eval(input())
    n=int(input())
    out=l[n: ]+l[ :n]
    print("After circulating the values are:",out)
```

## Output:
![Alt text](<Screenshot 2023-10-25 205811.jpg>)

## Result:
Circulation of the list has been executed successfully.
