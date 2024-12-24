# pca-from-scratch

This repository contains implementations of Principal Component Analysis (PCA) for both image and tabular datasets using Jupyter Notebooks. PCA is a dimensionality reduction technique that transforms high-dimensional data into a lower-dimensional space while preserving the most important information (variance).

## Datasets

*   **Image Data:** The [Unlabeled Stanford Dogs Dataset]
(https://www.kaggle.com/datasets/michaelfumery/unlabeled-stanford-dags-dataset)
is used for the image PCA implementation. This dataset contains images of various dog breeds.

*   **Tabular Data:** The [Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
The data has the target "Survived" (which we are excluding for this unsupervised learning task) is used for the tabular PCA implementation.
This dataset contains information about passengers on the Titanic.

## Notebooks

*   [`UL Project on Images Dataset.ipynb`](UL Project on Images Dataset.ipynb): Implements PCA on the Stanford Dogs image dataset. This notebook covers image loading, preprocessing (resizing, normalization, flattening), covariance matrix calculation, eigenvalue/eigenvector calculation, reconstruction, and visualization of reconstructed images and eigenimages.
*   [`UL Project on Titanic Dataset .ipynb`](UL Project on Titanic Dataset .ipynb): Implements PCA on the Titanic tabular dataset. This notebook covers data loading, preprocessing (handling missing values, scaling), covariance matrix calculation, eigenvalue/eigenvector calculation, selection of principal components, transformation, reconstruction error calculation, and visualization of explained variance.

## Key Concepts Demonstrated

*   **Mean Centering:** Shifting data to have a zero mean.
*   **Covariance Matrix:** Measuring the relationships between features.
*   **Eigenvalues and Eigenvectors:** Finding the directions of maximum variance.
*   **Dimensionality Reduction:** Projecting data onto a lower-dimensional space.
*   **Reconstruction:** Approximating the original data from the reduced representation.
*   **Explained Variance:** Quantifying the amount of variance captured by the principal components.
*   **Reconstruction Error:** Measuring the information loss due to dimensionality reduction.

## Results

*   For the image dataset, This figure illustrates the relationship between the number of principal components (k), the explained variance ratio, and the reconstruction error. Increasing k leads to higher explained variance and lower reconstruction error. 
   
![image](https://github.com/user-attachments/assets/cf833e0f-211e-437c-bf2d-ff4fa9525b95)
   
   
*   For the tabular dataset, This figure illustrates the trade-off between the percentage of variance explained by the principal components and the reconstruction error resulting from dimensionality reduction on the tabular data..
![image](https://github.com/user-attachments/assets/63a5b83b-0e2e-4fad-b9bf-6d7530594a87)
   

## Team Members:

*   Farah Mohamed
*   Nour ElDeen Ahmed
*   Zainab Tarek
*   Ali Mahmoud
*   Abdelfattah Mohamed
