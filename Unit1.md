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

## Write a python program to Circulate the n variables using function concept

# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the values from the user
### Step 2: 
Assign the value of variable to a temporary variable
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Print both the values it would be interchanged
### Step 6: 
End the program
## Program:

```
def circulate():
    b=a[n:]+a[:n]
    print("After circulating the values are:",b)
a=eval(input())
n=int(input())
```

## Output:
![OUTPUT](./images/FILENAME2.png)


## Result:
The output for circulate the values of n variables is successfull.



# EXP 3.

## Ram and Shyam were walking on a bridge. During their conversion, they were in need to find the length of the bridge. Write a program to find the distance of the bridge from one point to another point (display with 2 decimal points) second point coordinates- [10,6] and first point coordinates [4,2]

d=√((x_2-x_1)²+(y_2-y_1)²) 

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
Using import math function,do the calculations.
### Step 2: 
Take the two coordinates as l1 and l2.
### Step 3: 
Substitute the values in the distance formula

√((x_2-x_1)²+(y_2-y_1)²)

![formula](./images/formula.png)
### Step 4: 
using the print function, display the distance between the two points.
### Step 5: 
End the program.
### PROGRAM:

```
import math 
l1 = [4,2]
l2 = [10,6]
d = math.sqrt(((l2[0]-l1[0])**2)+((l2[1]-l1[1])**2))
print(f"{d:.2f}")
```

### OUTPUT:
![OUTPUT](./images/FILENAME3.png)

### RESULT:
The distance between the two points is sucessfully executed and displayed.





