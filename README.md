This project is regarding Machine Learning models for breast cancer predictions.

For best accuracy two models are developed
1. Logistic Regression
2. Support Vector Machine

Both the models are trained for efficient predictions and saved as
1. logisitic_model.sav
2. svm_model.sav

The models are trained using dataset available as Breast Cancer Wisconsin (Diagnostic) DataSet in Kaggle
The dataset can be downloaded from the below URL,
https://www.kaggle.com/uciml/breast-cancer-wisconsin-data

Attribute Information:

1) ID number
2) Diagnosis (M = malignant, B = benign)
3-32)

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
