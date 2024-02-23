Write a program to find a solution to a system of linear equations x-3y=0, 3x+y=10

```
import numpy as np
a = np.array([[1,-3],[3,1]])
b = np.array([0,10)
solution=np.linalg.solve(a,b)
print(solution)
```


Write a program to find the rank for the given matrix [[5,-3,-10],[2,2,-3],[-3,-1,5]]
```
import numpy as np
a = np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
solution=np.linalg.matrix_rank(a)
print(solution)
```
Write a python program to find the inverse of the given matrix

6  2 3
3  1 1
10 3 1

```
import numpy as np
A = np.array([[6,2,3],[3,1,1],[10,3,4]])
B = np.linalg.inv(A)
print(B)

```

Write a program to find the eigenvalues and associated eigenvectors for the matrix

[4,2],[2,4]
```
import numpy as np
A = np.array([[4,2],[2,4]])
values, vectors = np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))

```

![OUTPUT](./images/filename.png)
