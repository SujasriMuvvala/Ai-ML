STP_LinearAlgebra:
Generally, most of the machine learning data is stored in matrices.
Firstly, in this topic, we use matrix transpose for calucluations, multplications etc and then perform visulazing tranpose step. 
Shape checker: Checks whether the matrix can be multiplied or not
Conclusion: from this notebook, we learnt that linear algebra also, how to perform matrix multiplications using NUMPY, transpose, determinant, eigen values. And mainly about the Singular Value Decomposition
Lab Reflection Excercise:
Q.Observe the CPU time that multi_dot consumes as against CPU time that successive dot methods consume to arrive at the same solution. Which one is more efficient, why?
A. "multi_dot()" was more efficient, it automatically finds best order to multiply matrices, reducing computation time. 
Successive dot() operations follow fixed order, it can perform unnecessary calculations and take more time and longer.

