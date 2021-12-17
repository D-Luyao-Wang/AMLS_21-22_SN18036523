# AMLS_21-22_SN18036523
Applied Machine Learning Systems ELEC0134 (21/22) Assignment


The project can be downloaded via the link below
https://drive.google.com/file/d/1dftU2xYFre5RpPa8F-BfunCVtsQKk-8_/view?usp=sharing



## 1.brief introduction of the task

This project is to do two tumor classifiers, binary classifier and muti-calss classifier.

For binary classifier, the goal is to classify tumor and no tumor images. 

For muti-calss classifier, the goal is to classify meningioma tumor, glioma tumor, pituitary tumor or no tumor iamges.


## 2. description of the files

### 1. Data pre-processing

Images with the same label will be placed in a folder with the same name.

`Image_file_change.ipynb` is used to split the training data. 

`Image_file_change_test.ipynb` is used to split the test data. 


The data in `originaldata` file is original data which can be used for `Image_file_change.ipynb` and `Image_file_change_test.ipynb`

The data that has been classified can be downloaded directly at the link below
https://drive.google.com/file/d/1tb78FF5ISQHsbtGaq8ie3x__rQn4h4I3/view?usp=sharing

The file name is `preprocessed`.

In this file, the file `task1data` `test` is for Task A.

The file ``dataset`` `testcnn` is for Task A.



### 2. Task A. Binary classifier

The file name `task1data` in `preprocessed` file is training data for Task A.

The file name `test` in `preprocessed` file is testing data for Task A.


`task1svm.ipynb`  use Support Vector Machine to build binary classifier 

`task1knn.ipynb` use K-Nearest Neighbor (KNN) algorithm to build binary classifier 





### 3.Task A. Binary classifier

The file name `dataset` in `preprocessed` file is training data for Task B.

The file name `testcnn` in `preprocessed` file is testing data for Task B.


`task2knn.ipynb` use K-Nearest Neighbor (KNN) algorithm to build muti-class classifier 

`task2cnn.ipynb` use Convolutional Neural Networks algorithm to build muti-class classifier




## 4. How to run  code
 
Jupyter notebook should be used to run the code.



## 5.  Necessary packages or header files 

pandas
skimage
matplotlib
sklearn
torch
numpy
torchvision
PIL

`package.txt`shows all package.
