# PREDICTION OF BREAST CANCER DIAGNOSIS RESULT USING FEEDFORWARD NETWORK

## DATASET

This database is available through the UW CS ftp server: ftp ftp.cs.wisc.edu cd math-prog/cpo-dataset/machine-learn/WDBC/

Also can be found on UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29

Attribute Information:

1. ID number
2. Diagnosis (M = malignant, B = benign)

Ten real-valued features are computed for each cell nucleus:

a) radius (mean of distances from center to points on the perimeter)

b) texture (standard deviation of gray-scale values)

c) perimeter

d) area

e) smoothness (local variation in radius lengths)

f) compactness (perimeter^2 / area - 1.0)

g) concavity (severity of concave portions of the contour)

h) concave points (number of concave portions of the contour)

i) symmetry

j) fractal dimension ("coastline approximation" - 1)

All feature values are recoded with four significant digits.

Missing attribute values: none

Class distribution: 357 benign, 212 malignant

## GOOGLE COLAB

To predict this classification problem , Google colab notebook is used with the application of Numpy, Pandas, Scikit-learn and Tensorflow Keras.

## MODEL PREDICTION AND RESULT

The structure of the model has 4 dense layers which use activation function of 'relu' and followed by output layer using 'softmax'. 

Using sparse categorical crossentropy loss and and accuracy metric, the final result indicated that the training accuracy and validation accuracy is 100% and 96% respectively at epochs 20 with batch size of 10.
