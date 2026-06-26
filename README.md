# Python-File-Handling-NumPy-Notes
A beginner-friendly Python learning repository covering File Handling, NumPy, Basic Array Operations, and Array Sorting with detailed explanations, syntax, examples, and interview/exam-oriented notes.

Function	Description	Example

np.array()	Create an array	np.array([1,2,3])
np.zeros()	Array of zeros	np.zeros((2,2))
np.ones()	Array of ones	np.ones((3,3))
np.eye()	Identity matrix	np.eye(3)
np.arange()	Sequence with step	np.arange(1,10,2)
np.linspace()	Evenly spaced values	np.linspace(0,1,5)
np.reshape()	Change array shape	a.reshape(2,3)
np.flatten()	Convert to 1D	a.flatten()
np.sum()	Sum of elements	np.sum(a)
np.mean()	Average	np.mean(a)
np.max()	Maximum value	np.max(a)
np.min()	Minimum value	np.min(a)
np.sqrt()	Square root	np.sqrt(a)
np.sort()	Sort array	np.sort(a)
np.argsort()	Indices of sorted elements	np.argsort(a)

IMPORTANT :

Always import NumPy using import numpy as np.
Prefer using with open(...) for file handling because it automatically closes the file.
Remember the difference between file modes: "r" (read), "w" (overwrite/write), "a" (append), and "x" (create new file).
reshape() changes the dimensions of an array without changing its data (the total number of elements must remain the same).
np.sort() returns a sorted copy of the array; it does not modify the original array unless you assign the result back.
argsort() returns the indices that would sort an array, not the sorted values themselves.
