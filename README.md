# Breast_Cancer_Data_Visualization-
Reducing dimensions for data visualization of the Breast Cancer dataset using Unsupervised learning algorithm, PCA(Principal Component Analysis). 

#### PCA(Principal Component Analysis): 
Dimensionality reduction algorithm that identifies the hyperplane that lies closest to the data and then it projects the data onto it.

Dimensions are nothing but the features that represent the data. Example: A 28 * 28 image has 784 picture elements(pixels) that are the dimensions or features which together represent the image.

*In the given code information is extracted from the breast cancer dataset without using supervision.*

The task is performed in the following steps:
1. Preprocess the data to obtain dataframe consisting of all the features, their respective labels and feature labels.
2. Standardizing the data since PCA's output is influenced based on the scale of the features of the data.
3. Appy PCA to reduce the dimensionality of the dataset from 30 dimensions to 2 dimensions.

*In the code we have been able to retain 63.2% of the information.*

The visualization of data is as follows:
<p align="center">
  <img src="fig.png?raw=true" height="420" width=660" title="Data Visualization">
</p>
