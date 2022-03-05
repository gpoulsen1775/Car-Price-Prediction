# Car-Price-Prediction
I first pulled a dataset of used cars from Kaggle (URL: https://www.kaggle.com/nehalbirla/vehicle-dataset-from-cardekho). I then developed a momentum based  gradient descent algorithm that utilizes exponential coefficient weighting to find a minimum to a Mean Square Error function. This allowed me to fit a selection of model types to the data to try and extract a model for target variable price. I mostly attempted to predict price by mileage. My best model gave an R^2 of .15, which is low.  However, this low R^2 score is heavily tied to the amount of noise in the data. 

Fit contains my gradient descent algorithm. 
Linear Fitting contains a linear mapping from miles driven to price. 
Linear Plane contains a linear plane mapping from miles and year to price. 
Exponential Decay contains an exponential mapping from miles to price. 
