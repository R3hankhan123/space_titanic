
# Space Titanic

It is a binary prediction model for a kaggle competition. In datasheet any outliers were removed from the training data set. First the model was trained with cabin as ordinally encoded and rest of the categorical data was one hot encoded but the accuracy was increased when the cabin column was dropped.For any missing categorical data another column was created to indicate weather the categorical data was there previously or not.

# Model 1
It employes XGB boost as one model and Random Forrest Regressor as another one. Which ever has a higher accuracy that model is selected

# Model 2
It uses a neural network made using Tensorflow