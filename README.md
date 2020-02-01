# TIL
Today I Learned..

# math
eigenvalue
eigenvaector
eigen-decomposition
eigenvalue decompositon

# python code
import numpy as np
import pandas as pd

A = np.array([[1, -2], [2, -1]])
w1, V1 = np.linalg.eig(A)
print(w1)
print(V1)
