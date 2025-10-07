//inner-workings of LLM

## What is a tensor? 
A tensor is a mathematical object that generalizes the idea of scalars, vectors, and matrices to higher dimensions.
Basically its like matrices but it is able to represent multiple higher dimensions.
Scalar (0-D tensor): Just a single number (e.g., 5).

Vector (1-D tensor): A list of numbers in a single dimension (e.g., [1, 2, 3]).

Matrix (2-D tensor): A table of numbers with rows and columns (e.g.,[[1, 2, 3], [4, 5, 6]] )

 ### Example (3-D Tensor):

Imagine we have 2 grayscale images, each 3×3 pixels:
Image 1:
[[1, 2, 3],
 [4, 5, 6],
 [7, 8, 9]]

Image 2:
[[10, 11, 12],
 [13, 14, 15],
 [16, 17, 18]]

We can represent this as a 3-D tensor of shape (2, 3, 3):
[
 [[1, 2, 3],
  [4, 5, 6],
  [7, 8, 9]],

 [[10, 11, 12],
  [13, 14, 15],
  [16, 17, 18]]
]

Here:
- First dimension = which image (2 of them).
- Second dimension = row of pixels.
- Third dimension = column of pixels.
  