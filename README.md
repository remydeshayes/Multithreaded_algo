# Multithreaded Algorithm    

Authors : Rémy Deshayes and Sarah Lauzeral

This is a **<ins>very early-stage</ins>** shot at implementing a Parallel Lasso with Cython.

Over the years, the amount of available data has sky-rocketed to the extent that some training datasets cannot be stored in a single machine memory.       
In that case, traditional subgradient methods such as the Coordinate Descent algorithm - focus of this project - can no longer be used. Indeed, Python and R packages often kick off by loading the entire dataset on the RAM. 

#### An interesting paper on the matter:
[1] _Distributed Coordinate Descent for L1-regularized Logistic Regression_, Ilya Trofimov, Alexander Genkin (2015)
