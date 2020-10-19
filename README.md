# Machine Learning Classification  Algorithms Comparison 

# KNN
K-nearest neighbors is a non-parametric method used for classification and regression. It is one of the most easy ML technique used. It is a lazy learning model, with local approximation.

# Decision tres
Decision tree is a tree based algorithm used to solve regression and classification problems. An inverted tree is framed which is branched off from a homogeneous probability distributed root node, to highly heterogeneous leaf nodes, for deriving the output. Regression trees are used for dependent variable with continuous values and classification trees are used for dependent variable with discrete values.

# Logistic Regression
 Logistic regression is the right algorithm to start with classification algorithms. Eventhough, the name ‘Regression’ comes up, it is not a regression model, but a classification model. It uses a logistic function to frame binary output model. The output of the logistic regression will be a probability (0≤x≤1), and can be used to predict the binary 0 or 1 as the output ( if x<0.5, output= 0, else output=1).

# Logistic Regression vs Decision Tree
Decision tree handles colinearity better than LR.
Decision trees cannot derive the significance of features, but LR can.
Decision trees are better for categorical values than LR.

# Logistic Regression vs KNN 
KNN is a non-parametric model, where LR is a parametric model.
KNN is comparatively slower than Logistic Regression.
KNN supports non-linear solutions where LR supports only linear solutions.
LR can derive confidence level (about its prediction), whereas KNN can only output the labels.

# Decision tree vs KNN
Both are non-parametric methods.
Decision tree supports automatic feature interaction, whereas KNN cant.
Decision tree is faster due to KNN’s expensive real time execution.

# Results
Accuracy 
Precision
F1-score

# Dataset set
Diabetic Patient data set available on https://archive.ics.uci.edu/ml/datasets/diabetes+130-us+hospitals+for+years+1999-2008
