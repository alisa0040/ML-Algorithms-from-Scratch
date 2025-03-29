# ML-Algorithms-from-Scratch
A collection of machine learning algorithms implemented without external libraries, focusing on fundamental concepts.  
These implementations were created as part of my university coursework and personal learning.  

## Implemented Algorithms  
-  Gradient Descent for Linear Regression  
-  Gradient Descent for Logistic Regression  
-  K-Means Clustering for Image Compression

-  ## Repository Structure  
📂 **Notebook (.ipynb)** – Full implementation and explanation.  



## K-Means Image Compression

This project implements the **K-Means** clustering algorithm from scratch to compress images by reducing their color palette while preserving visual quality.

### Features:
- **K-Means Clustering**: Divides the image into `k` color clusters.
- **Compression**: Replaces each pixel with the nearest cluster centroid, reducing image size.
- **No External Libraries**: Uses only **NumPy** for calculations.

### How it Works:
1. Randomly initialize `k` centroids.
2. Assign each pixel to the nearest centroid based on Euclidean distance.
3. Update centroids by averaging the pixels in each cluster.
4. Replace original pixels with final centroids.

### Results:
- Compresses the image with adjustable `k` clusters for balancing quality and compression.
