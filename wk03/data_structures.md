---
jupytext:
  formats: ipynb,md:myst
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.10.3
kernelspec:
  display_name: Python 3 (ipykernel)
  language: python
  name: python3
---

# Data Structures

## EOSC 211

**Week 3**

**Learning Objectives:**  
1. Introduce numpy arrays
2. Use some of numpy's built in functions to generate arrays efficiently
2. Use slicing to access and change elements of an array 

Useful references:

[Course Reading on Numpy Arrays](https://phaustin.github.io/Problem-Solving-with-Python/NumPy-and-Arrays/Introduction.html)

[Numpy Documentation](https://numpy.org/doc/stable/reference/generated/numpy.array.html)

```{code-cell} ipython3
# import the numpy package - an extension of python's core built in functions
import numpy as np
```

### Question 1: Generating Arrays

Some built-in functions (functions that come with the numpy package) which may be useful:

```python
    np.arange()
    np.zeros()
    np.ones_like()
    np.linspace()
    my_array.shape
    my_array.T
```
    
There are several correct ways to do each of these; some strategies are better than others. Have a look at the [numpy documentation](https://numpy.org/doc/stable/reference/generated/numpy.array.html) for help using numpy's built in functions

**A) Represent the following vector as a numpy array called `var1`**

$$
(1.1, 2.2, 3.3, 4.4, 5.5) 
$$

```{code-cell} ipython3
# your code here
```

**B) Create a numpy array called `var2` with numbers 0 to 10**

```{code-cell} ipython3
# your code here
```

**C) Create a numpy array called `var3` containing all odd numbers (in order) from 0 to 1000**

```{code-cell} ipython3
# your code here
```

**D) Represent the following matrix as a numpy array called `var4`**

$$
\begin{pmatrix}
1 & 1 \\
2 & 3 \\
5 & 8
\end{pmatrix}
$$

```{code-cell} ipython3
# your code here
```

**E) Is `var4` a 2 x 3 array or a 3 x 2?**

```{code-cell} ipython3
# your code here
```

**F) Make an array called `var5` that looks like this. (hint: you shouldn't have to type it all out)** 

$$
\begin{pmatrix}
1 & 2 & 5\\
1 & 3 & 8\\
\end{pmatrix}
$$

```{code-cell} ipython3
# your code here
```

**G) Create an array called `var6` with 10 rows and 5 columns where all elements are zero**

```{code-cell} ipython3
# your code here
```

**H) Create an array called `var7` that has 5 rows and 10 columns where all elements are the number 1**

```{code-cell} ipython3
# your code here
```

## Question 2: Array Slicing

**A) Use slicing to get the 3rd element in `var1`. REMEMBER that in Python we count starting from zero, so the first element of an array would look like `my_array[0]`**

```{code-cell} ipython3
# your code here
```

**B) The 2nd, 3rd, and 4th elements of `var1`**

```{code-cell} ipython3
# your code here
```

**C) The last 20 elements in `var3`**

```{code-cell} ipython3
# your code here
```

**D) The element in the third row and second column of `var4`**

```{code-cell} ipython3
# your code here
```

**E) The last column of `var5`**

```{code-cell} ipython3
# your code here
```
