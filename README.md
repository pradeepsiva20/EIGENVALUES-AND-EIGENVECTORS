# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm: 

### Step1 :
    Import the numpy module to use the built-in functions for calculation
### Step 2:
    Prepare a list for each linear equation and assign in numpy.linalg()
### Step 3: 
    Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
    Print the eigen value and eigen vector using print() function.End the program
## Program:
   ```
    #program to find the Eigen values and Eigen Vectors
    #Developed by: PRADEEP.S 
    #RegisterNumber:22009034
    
    import numpy as np
    A=np.array([[4,2],[2,4]])
    values,vectors=np.linalg.eig(A)
    print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
   ```
## Output:  
   ![Eigen values -and- Eigen vectors](https://user-images.githubusercontent.com/120539823/211203296-095eff7b-7400-4a7c-b082-d4d1aba0b172.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
