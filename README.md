# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation

### Step 2: Prepare the lists from the matrix and assign in np.array()

### Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: End the program. 

## Program:
```
#Developed by: NETHRA.K
#Register Number: 212224230184


import numpy as np

A = np.array([[2, 2],[1, 3]])


eigenvalues, eigenvectors = np.linalg.eig(A)

print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvectors}")

```

## Output:

<img width="1542" height="981" alt="Screenshot 2025-08-20 113414" src="https://github.com/user-attachments/assets/0b7ff17d-1119-4a21-9c2f-e7a5669159fb" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
