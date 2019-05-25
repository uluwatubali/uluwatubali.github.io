# uluwatubali.github.io

Notes
## Essence of linear algebra

https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab

+ Span of basis vectors
+ Linear Transformation: M * v = w
  - Transform: Rotation, Squeeze , Scale...etc"
+ Matrix Multiplication: 
  - M1 * M2 * v: Means transform v by M2 first and then by M1
  - M1 * M2 * v = M1 * (M2 * v) = M1 * v' = w
+ The Determinat: det(M)
  - Determinant = Scaling Factor to the original space
  - det(M) < 0: means flip orientation
  - det(M) != 0: 
    - Transform to the same dimention number. 
    - There is always an inverse transformation of M: M'
+ Inverse Matrix: Transform Backward!
  - M * v = w ==> w * M' = v, M' is inverse Matrix of M
  - M * M': Transform foward and then transform backward = Do nothing.
  - M * M' = I, I: Identiy Matrix, I * v = v
  - Useful to calculate unknow variable
    - example: M * x = v
    - x is unknown, v is known. M * x = v == > M' * M * x = M' * v ==> I * x = M' * v ==> x = M' * v
    - There is always unique solution <===> M' exist <==> det(M) != 0 
+ Column Space and Null Space
  - Column Space of M: M * v ==> v can be span to all of vecors in M
  - Null space = All the points squeezed to zero point
    - M * x = 0, All of solutions of x are in Null Space
  
## Header 2
## Header 3

- List 1
- List 2
