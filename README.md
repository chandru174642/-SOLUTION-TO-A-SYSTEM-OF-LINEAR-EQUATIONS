# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
```
#Program to find the solution for the given linear equations.
#Developed by: CHANDRU P
#RegisterNumber:23007250
import numpy as np
a=[5,-3,-10],[2,2,-3],[-3,-1,5]
b=[-9,4,-1]
c=np.linalg.solve(a,b)
print(c)
```
## Output:
![Screenshot 2023-12-24 105134](https://github.com/chandru174642/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/139841798/06e2a05b-5193-4c72-8f57-e913fbe9cba3)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

