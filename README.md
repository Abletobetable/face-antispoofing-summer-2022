# face-antispoofing-summer-2022
1. run_dataset.ipnb getting local binary patterns(lbp) features for the datasets:
  
  https://drive.google.com/file/d/1uBH6JYkAgy1HHMxTTP39XdZOMtHWc2qG/view?usp=sharing
  
  https://drive.google.com/file/d/1uATAPZSwJBy5oj6AYLqQrEsy0dhJrI0Y/view?usp=sharing
  
  You need to load this files into your google drive
  
2. lbp features calculated by feature_extract.py from https://github.com/Elroborn/Face-anti-spoofing-based-on-color-texture-analysis

3. spoofing_classicML.ipnb build classic models from sklearn using features from step 2



## Features:

zip file for data_128: https://drive.google.com/file/d/1MoNuWJxP0eoC2s2Ql8BGf4P970ejJVXQ/view?usp=sharing

zip file for data_256: https://drive.google.com/file/d/19SI-l9qSHLhhyncqNHgHMgdgKFXvTN6t/view?usp=sharing

## Classic ML models results:

Data_128:

PCA: it's not separating well

Logistic Regression: f1 = 0.78

SVM: f1 = 0.88

Knn: f1 = 0.83

Gaussian Naive Bayes: f1 = 0.70

Decision Tree: f1 = 0.77

Random Forest: f1 = 0.87

AdaBoost: f1 = 0.81

Multi-layer Perceptron: f1 = 0.91



Data_256:

PCA: separates a little better

Logistic Regression: f1 = 0.87

SVM: f1 = 0.94

Knn: f1 = 0.86

Gaussian Naive Bayes: f1 = 0.75

Decision Tree: f1 = 0.87

Random Forest: f1 = 0.93

AdaBoost: f1 = 0.90

Multi-layer Perceptron: f1 = 0.97
