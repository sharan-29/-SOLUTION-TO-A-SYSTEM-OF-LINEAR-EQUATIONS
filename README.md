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
Developed by: Sharan Kumar G
RegisterNumber:24003909
import numpy as np
A=[[5,-3,-10],[2,2,-3],[-3,-1,5]]
b=np.array([-9,4,-1])
c=np.linalg.solve(A,b)
print(c)
```

## Output:
![image](https://github.com/user-attachments/assets/eb15c89a-be3c-4181-af46-b4cab4b71c8c)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

