# Singular Value Decomposition

Singular Value Decomposition (SVD) is a fundamental technique in linear algebra used to factorize a matrix. It has widespread applications in machine learning, signal processing, and image compression. It is given by the following formula:  

$A = U \Sigma V^T$  

- U: An orthogonal matrix whose columns are the left-singular vectors.
- $\Sigma$: A diagonal matrix containing the singular values of A, which are always non-negative and are typically sorted in descending order. These values represent the "importance" of different components of the original matrix.
- $V^T$: An orthogonal matrix whose columns are the right-singular vectors.

Singular Value Decomposition (SVD) is used in image compression by decomposing an image matrix into three components which capture the image’s structural information. By retaining only the top k singular values and their corresponding vectors, we can construct a low-rank approximation of the original image that visually preserves key features while significantly reducing storage. This method exploits the fact that many singular values contribute minimally to image detail, allowing for effective compression with minimal loss in quality to the human eye.

# Data

The data used here is an image of Rice's Lovett Hall, found here: https://www.houstonchronicle.com/local/gray-matters/article/What-a-Houston-style-architecture-might-look-5930192.php

# Libraries
The following python libraries are used.

matplotlib (https://matplotlib.org/)  
numpy (https://numpy.org/)  
PIL (https://pillow.readthedocs.io/en/stable/)
