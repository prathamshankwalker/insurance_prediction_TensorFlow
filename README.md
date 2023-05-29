# insurance-prediction--regression-

## Problem Statement:
predict the cost of medical insurance for individuals based on a number of different parameters such as, age, sex, bmi, children, smoking_status and residential_region.

#### Libraries used
- TensorFLow, Keras, Scikit-Learn, Pandas, etc.
#### Description
- Simple Regression model to predict the cost of insurance based on various parameteres.
- Dataset used : [(https://raw.githubusercontent.com/stedy/Machine-Learning-with-R-datasets/master/insurance.csv](https://raw.githubusercontent.com/stedy/Machine-Learning-with-R-datasets/master/insurance.csv)
 ##### Model : 
 - Used keras Sequential Api to make a simple 4 layer (Dense) TensorFlow model.
 -The top 3 layers has Activation function ''relu" followed by the Output Dense layer with no activation function(Default).
 - The model was compiled with the Adam optimizer and loss metric as mae (mean abolute error)
 - Train-Test-Split - The data was split with 80% for training and 20% for test.
 - The model was trained for 200 epochs which attained a validation mae of 1724.
