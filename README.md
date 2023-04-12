# Numpy-in-Python
Numpy helps to create arrays,matrix functions like arange, linspace,zeros,ones,eyes, sqrt,unique &amp; random can be used.

import numpy as np

#for creating vectors
Vec=np.array([1,2,3,4,5,6,7,8,9,10,11])
print(Vec)

#for creating matrix
Matrix= np.array([[1,2,3], [4,5,6],[7,8,9]])
print (Matrix)

#transpose of matrix
print(Matrix.T)

#find out sqaureroot of 99900
x=np.sqrt(99900)
print(x)

#functions for arrays

#arange- 1st no. is included but not the last one.
vec1=np.arange(0,300)
print(vec1)

#linspace:- linear spacing where both 1st and last is inclusive
vec3=np.linspace(0,20,10)
print(vec3)

#reshape- it reshapes the vector into matrix
vec3.reshape(5,2)

#to make one and zero matrix

mat2=np.zeros([4,4])
print(mat2)

mat3=np.ones([5,5])
print(mat3)

#identity matrix
mat5=np.eye(6)
print(mat5)

# addition, substraction, multiplication and division of vectors (of same size)
vec1=np.arange(1,6)
print(vec1)
vec2=np.arange(5,10)
print(vec2)
vec1+vec2
vec1-vec2
vec1/vec2
vec1*vec2

#to find out unique value in array
vec7=np.array(["orange","red","1","purple","raksha","orange","rice"])
print(vec7)

print(np.unique(vec7))

#to generate random variable in matrix form
rand_mat=np.random.rand(10,10)
print(rand_mat)

#mean,max,min of matrix
z=np.mean(rand_mat)
print(z)

np.max(rand_mat)

np.min(rand_mat)



