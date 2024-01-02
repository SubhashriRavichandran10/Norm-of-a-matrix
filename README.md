# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No:23012776
# Developed By:R.SUBHASHRI
# 1-Norm of a Matrix
```
# Register No:212223230219
# Developed By:R SUBHASHRI
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)


```



# 2-Norm of a Matrix

```
'''
Program to find 2-norm of a matrix.
Developed by:R.Subhashri
RegisterNumber:212223230219
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```


# Infinity Norm of a Matrix


```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



```



## Output:
### 1-Norm of a Matrix
![Screenshot 2024-01-02 212435](https://github.com/SubhashriRavichandran10/Norm-of-a-matrix/assets/145743413/b8287e64-067e-40f7-9c71-22343f2214e7)


### 2-Norm of a Matrix



![Screenshot 2024-01-02 212449](https://github.com/SubhashriRavichandran10/Norm-of-a-matrix/assets/145743413/1d1727aa-d8dd-4b57-8c95-c4584c034cc5)




### Infinity Norm of a Matrix






![Screenshot 2024-01-02 212507](https://github.com/SubhashriRavichandran10/Norm-of-a-matrix/assets/145743413/68d9289c-1e38-482f-a6a2-3da5540cb0ba)




## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
