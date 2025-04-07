# ML-Algorithms-from-Scratch
A collection of machine learning algorithms implemented without external libraries, focusing on fundamental concepts.  
These implementations were created as part of my university coursework and personal learning.  

## Implemented Algorithms  
-  Gradient Descent for Linear Regression  
-  Gradient Descent for Logistic Regression
-  Logistic Regression with Cross-Validation and Confusion Matrix
-  K-Means Clustering for Image Compression

-  ## Repository Structure  
📂 **Notebook (.ipynb)** – Full implementation and explanation.  



### Gradient Descent for Linear Regression

This implementation demonstrates the use of the Gradient Descent algorithm to optimize parameters for a simple linear regression model. The model is used to predict the target variable based on two input features. The algorithm minimizes the error between the predicted and actual values by iteratively adjusting the model parameters.

Key points:
- **Simple Linear Regression**: Predicts `y = θ₀ + θ₁ * X₁ + θ₂ * X₂`.
- **Gradient Descent**: Updates parameters (`θ₀`, `θ₁`, `θ₂`) based on the gradients of the error.
- **Implementation**: Built from scratch using only NumPy, with no external machine learning libraries.


### Gradient Descent for Logistic Regression

This implementation demonstrates the use of the Gradient Descent algorithm for logistic regression. The logistic regression model predicts binary outcomes based on input features by applying a sigmoid function to the weighted sum of the inputs.

Key points:
- **Logistic Regression**: Used for binary classification tasks (e.g., 0 or 1).
- **Sigmoid Activation**: The model applies the sigmoid function to make predictions between 0 and 1.
- **Gradient Descent**: Updates model parameters based on the gradient of the error.
- **Implementation**: Built from scratch using only NumPy, with no external machine learning libraries.


## Logistic Regression with Cross-Validation and Confusion Matrix

This implementation extends the basic logistic regression model by adding functionality for model evaluation using k-fold cross-validation and a confusion matrix. These metrics help to better understand the model’s performance and ensure it generalizes well.
The model was tested on the Diabetes Dataset, where the task is to predict whether a patient has diabetes based on several medical attributes.

Key points:
- **Logistic Regression**: Predicts probabilities for binary classification tasks using the sigmoid function.
- **k-Fold Cross-Validation**: Splits the dataset into k subsets for training and testing, ensuring a more reliable performance estimate.
- **Confusion Matrix**: Computes key performance metrics (accuracy, precision, recall, F1-score) to evaluate the model’s performance.
- **Dataset**: The model was tested using the Diabetes Dataset, where the goal is to classify individuals as diabetic or not based on several features.
- **Implementation**: Built from scratch using only NumPy, with no external machine learning libraries.

 
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
