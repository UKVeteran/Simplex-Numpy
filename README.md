## Creating a Linear Program Solver by Implementing the Simplex Method in Python with NumPy

Simplex Algorithm is a popular algorithm for linear programming... [link to Wikipedia!](https://en.wikipedia.org/wiki/Simplex_algorithm) :grinning:


The example in [Simplex.py](https://github.com/Reda-BELHAJ/Simplex_Numpy/blob/main/simplex.py) is :

        [ 0 2 1 ]      
    A = [ 0 1 1 ]   b = [ 20 18 8 ]  c = [ 1 -7 -4 ]
        [ 0 1 0 ]   
        
And i already test some random inputs with the use of random function in numpy:
```
    A = np.random.randint(-25, 25,size = (SIZE_MATRIX_X, SIZE_MATRIX_Y))
    b = np.random.randint(-25, 25,size = SIZE_MATRIX_X)
    c = np.random.randint(-25, 25,size = (1, SIZE_MATRIX_Y))
```
