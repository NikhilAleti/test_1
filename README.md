The original Wisconsin-Breast Cancer (Diagnostics) dataset (WBC) from UCI machine learning repository is a classification dataset, which records the measurements for breast cancer cases. There are two classes, benign and malignant. The malignant class of this dataset is downsampled to 21 points, which are considered as outliers, while points in the benign class are considered inliers.
It is a dataset of Breast Cancer patients with Malignant and Benign tumor.
Logistic Regression and K-nearest algorithm is used to predict whether the given patient is having Malignant or Benign tumor based on the attributes in the given dataset.
At first necessary libarries are imported
Then the dataset is uploaded and read
Unnecesary coloumns are dropped as they do not have any contribution
Then is data is normalized and splitted for testing and traing and the respective ML model is performed on the dataset.
