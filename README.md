# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
## Step 1:
start the program

## Step 2:
get into the input from the user usind eval(input())

## Step 3:
Get the value from the user for the number of rotation

## Step 4:
Using the slicing concept rotate the list

## Step 5:
using concentration operation display the entire rotated list

## Step 6:
stop the program
### PROGRAM:
```
 #Program to find the distance between two points.
#Developed by: singamala venakata sai kumar reddy
#RegisterNumber:23004205
import math
def calculate_distance(x1, y1, x2, y2):
    distance = math.sqrt((x2 - x1)**2 + (y2 - y1)**2)
    return round(distance, 2)
x1,y1 = 4, 2
x2,y2= 10, 6
bridge_length = calculate_distance(x1, y1, x2, y2)
print(f"{bridge_length}") 
```

### OUTPUT:
![image](https://github.com/23004205/DISTANCE-BETWEEN-TWO-POINTS/assets/138971114/5f890cb3-cf5f-4d80-a2f3-93423d4d9322)


### RESULT:
Thus the Distance between of two points are sucessfully executed.
