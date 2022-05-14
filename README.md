
# Principal Component Analysis (PCA) on Olivetti Images

PCA is applied on images for a number of reasons. They are:

**Number of features:** Images have huge number of features. Even a small image of 28 x 28 pixels will have 784 features to deal with.

**Lot of Covariance:** When you look at an image, it is easy to understand that if we have the values for one pixel 'p', the pixels in the vicinity of 'p' will generally have similar values.

Other fundamental reasons to apply PCA are that it **reduces memory consumption and time taken.**

In this project,  PCA on Olivetti Images dataset is applied, and a  Random Forest Classification model is created for the same.

We compare the resultant accuracy with the accuracy obtained for the Model without using PCA.

Classification Model after applying PCA takes lesser time and gives 93% accuracy on the test data, while Model without PCA gives 92% accuracy and takes more time.

