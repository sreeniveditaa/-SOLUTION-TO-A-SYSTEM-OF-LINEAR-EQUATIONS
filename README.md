# DATE :
# EXP 01 :SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
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
#Developed by: Sree Niveditaa Saravanan
#RegisterNumber: 212223230213
```
```
import numpy as np
a = np.array([[1,-3],[3,1]])
b = np.array([0,10])
c = np.linalg.solve(a,b)
print(c)
```
## Output:

![image](https://github.com/user-attachments/assets/902df3a6-abb6-41fb-9081-381c8d7e2959)

![image](https://github.com/user-attachments/assets/23950d25-3f42-45f2-8876-b4d774ab0bb8)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

