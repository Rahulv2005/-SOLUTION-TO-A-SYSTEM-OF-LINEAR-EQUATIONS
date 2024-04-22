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
#Developed by: RAGHUL V
#RegisterNumber: 212223240132

import numpy as np
a = np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
b = np.array([-9,4,-1])
solution=np.linalg.solve(a,b)
print(solution)
```
## Output:
![image](https://github.com/Rahulv2005/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/152600335/ae81df0a-a507-418d-938c-bc263c2e3182)
![image](https://github.com/Rahulv2005/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/152600335/d286d868-e9de-485c-ba4e-c2b27ed9593e)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

