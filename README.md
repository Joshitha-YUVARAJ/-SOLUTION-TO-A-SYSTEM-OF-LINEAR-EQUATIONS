## DATE:
## EX-1 SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
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
import numpy as np
a = np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
b = np.array([-9,4,-1])
solution=np.linalg.solve(a,b)
print(solution)
```
## Output:
![Screenshot 2024-08-29 084801](https://github.com/user-attachments/assets/b379a4a3-c882-4f32-bc5e-eb8fa982932c)

![Screenshot 2024-08-29 084848](https://github.com/user-attachments/assets/578264ca-845e-4921-a932-f268a29e567c)




## Result: 
Thus the solutions for the linear equations are successfully solved using python program

