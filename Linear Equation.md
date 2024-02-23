Write a program to find a solution to a system of linear equations x-3y=0, 3x+y=10

```

import numpy as np
a = np.array([[1,-3],[3,1]])
b = np.array([0,10)
solution=np.linalg.solve(a,b)
print(solution)

```
