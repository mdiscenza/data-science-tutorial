# Session 1: Intro and Linear Regression 2/17/2018 
Goals:
- overview of what we want to do and tools/approach and [objectives](../objectives.md)
- linear regression

#### Linear Regression concepts to understand  
Linear Regression (linear algebra perspective):
https://dsgazette.com/2018/01/10/linear-regression-by-hand/

Linear Regression (numerical perspective - gradient descent-- minimization):
https://eli.thegreenplace.net/2016/linear-regression/

Matrix definition:
https://onlinecourses.science.psu.edu/stat501/node/382


- Jupyter Notebook
- Matplotlib

#### Session 1 Homework:

Go through linear regression lower lever to higher level of abstraction - first the linear algebra, then least squares estimator (ordinary lease squares for minimizimg error terms), and finally SciKitLearn which is the statistics package that most people use in python. You'll both generate your own data (good for sanity checks and demostration) and use datasets that you find elsewhere.

1. Set up Jupyter Notebook
1. Follow this example for linear regression using numpy only -- just matrix operations - http://anwarruff.com/normal-equation/ This is a toy example where a line can go through all of the points.
1. With the previous code, set up an example where a line will not perfectly go through all of the points- you'll need to generate another data set for this. 
1. Now you can use `linalg.lstsq` function to caluate least squares estimator -- this is finding a minium https://glowingpython.blogspot.com/2012/03/linear-regression-with-numpy.html See if you can verify that it's doing the same thing as you were doing in the previous approach
1. Follow the previous examples but generate a new data set (you can generate the data from distributions with differe parameters). 
1. Follow [this example](https://jakevdp.github.io/PythonDataScienceHandbook/05.06-linear-regression.html) for "Simple Linear Regression" section only and reproduce the dataset and graphs. Reporduce this in your Jupyter Notebook
1. Follow the steps above for your own dataset
    - find a real *bivariate* data set somewhere and load it into your session
    - graph your data
    - apply the ScikitLearn Linear Regression function to fit a model for your dataset
    - calcuate MSE for your model on your own 

We'll hold off on the Titanic stuff until we get through classification/logistic regression next time.