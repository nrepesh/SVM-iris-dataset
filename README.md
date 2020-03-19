# SVM-iris-dataset

We will be using the famous Iris flower data set.

The Iris flower data set or Fisher's Iris data set is a multivariate data set introduced by Sir Ronald Fisher in the 1936 as an example of discriminant analysis.

The data set consists of 50 samples from each of three species of Iris (Iris setosa, Iris virginica and Iris versicolor), so 150 total samples. Four features were measured from each sample: the length and the width of the sepals and petals, in centimeters.

I used Pandas for data analysis and Matplotlib/seaborn for data visualization.

Cleaned data and fitted a support vector machine model and used it to classify flowers. Finally, I evaluated the results using an evaluation matrix.

Udemy course - Python for Data Science and Machine Learning Bootcamp

This idea of creating a 'grid' of parameters and just trying out all the possible combinations is called a Gridsearch, this method is common enough that Scikit-learn has this functionality built in with GridSearchCV! The CV stands for cross-validation.

GridSearchCV takes a dictionary that describes the parameters that should be tried and a model to train. The grid of parameters is defined as a dictionary, where the keys are the parameters and the values are the settings to be tested. higher the number, the more verbose (verbose just means the text output describing the process).
