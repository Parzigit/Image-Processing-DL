**Image Classification Using SVM with K-means clustering and Sequential-CNN**


Creating a Sequential CNN model to classify images of various datasets and comparing the results to that of an svm model(image classification) with k-means clustering(image clustering).
**Final Results:**

Using **SVM & k-Means**

![image](https://github.com/Parzigit/Image-Processing-DL/assets/127716273/5b3fc435-a33f-4141-9beb-96e49243d09b)

Using **Seq-CNN**

![image](https://github.com/Parzigit/Image-Processing-DL/assets/127716273/ce5dc34f-6899-4f09-ad74-1df65f33baa2)


**A Sequential model is not appropriate when:**

->Your model has multiple inputs or multiple outputs

->Any of your layers has multiple inputs or multiple outputs

->You need to do layer sharing

->You want non-linear topology (e.g. a residual connection, a multi-branch model)


**An SVM model is not appropriate when:**

->SVM algorithm is not suitable for large data sets.

->SVM does not perform very well when the data set has more noise i.e. target classes are overlapping. In cases where the number of features for each data point exceeds the number of training data samples, the SVM will underperform.

->As the support vector classifier works by putting data points, above and below the classifying hyperplane there is no probabilistic explanation for the classification.
