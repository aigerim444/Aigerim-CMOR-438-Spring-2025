# Using Singular Value Decomposition for Image Compression

This directory implements **Singular Value Decomposition (SVD)** to perform Image Compression. 

SVD is a matrix factorization technique that decomposes a matrix into three matrices: 'U', 'S', and 'V^T'. These matrices capture the underlying structure and patterns of the matrix, and in this case our image will be represented by this matrix.
To compress the image, we reconstruct it using only the top `r` singular values and corresponding vectors. 
This is called a **rank-`r` approximation**

This is a great example of how linear algebra can used in image compression and dimensionality reduction.

### Data Used
- Input Image: a picture I took of a flower, at `pic/flower.jpg`
    - The image is converted from RGB to grayscale using the average of the color channels.
    - It is stored as a 2D NumPy array, where each entry represents a pixel intensity value.      

In the notebook for this section, we go through the process of decomposing the image and reconstructing the image using different values of `r`.
### Libraries used
```bash
pip install numpy matplotlib 