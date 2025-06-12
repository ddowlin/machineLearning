Python Notebook
================

``` python
import os
os.system("pip3 install matplotlib")
```

    ## 0

``` python
import numpy as np
import matplotlib.pyplot as plt
#plt.style.use('./deeplearning.mplstyle')
```

``` python
# x_train is the input variable (size in 1000 square feet)
# y_train is the target (price in 1000s of dollars)
x_train = np.array([1.0, 2.0])
y_train = np.array([300.0, 500.0])
print(f"x_train = {x_train}")
```

    ## x_train = [1. 2.]

``` python
print(f"y_train = {y_train}")
```

    ## y_train = [300. 500.]
