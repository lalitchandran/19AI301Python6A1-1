# EXP 1. 
## The boys Surya and Vijay had been playing switch and swap every time it suited their fancy since they had shared two balls. They had a temporary basket to drop the ball for swapping from each other. Write a python program to swap the colour of balls between Surya and Vijay.

## AIM:
To write a python program for swapping of two values
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Get the two values from the user
### Step 2: 
Assign the value of second variable to a temporary variable 
### Step 3: 
Assign the value of the first variable to the second variable.
### Step 4:  
Assign the value in temporary variable to the first variable
### Step 5: 
Print both the values it would be interchanged
### Step 6: 
End the program
## PROGRAM:

```
x = eval(input())
y = eval(input())
temp = x
x = y
y = temp
print("Swapped values are:",x,y)
```
## Output:
![OUTPUT](./images/FILENAME.png)


## Result:
The output for circulate the values of n variables is successfull.


# EXP 2.


```
def circulate():
    b=a[n:]+a[:n]
    print("After circulating the values are:",b)
a=eval(input())
n=int(input())
```
