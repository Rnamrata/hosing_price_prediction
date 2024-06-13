# house_sale_price_prediction

This report is about predicting housing sale prices. To predict the prices two data sets were used, one is the Housing_Data_Train.csv and another one is Housing_Data_Test.csv.

Imagine you have a dataset of houses with various features like size, number of bedrooms, when built, when sold, condition of garage, basement, electricity, heating, air condition etc., and you want to predict their prices. The goal is to build a model that makes accurate predictions considering the core features as the maximum potential of a house.

Here's what the code does:

It starts by loading the housing data and finding the major features undergoing different steps of data pre-processing

Then, it splits the data into two parts: the "training" set and the "validation" set. The training set is used to teach the model how to make predictions, and the validation set is used to check how well the model is doing.

The code creates a linear regression model, which is a way to make predictions based on the data.

It trains the model using the training data, so the model learns from the features of the houses and their actual prices.

After training, the model makes predictions on the validation set and calculates how accurate those predictions are.

It repeats these steps while varying the complexity of the model. In simpler terms, it tries to build models that could predict target value with accuracy incorporating changes in the elemental data.

Finally, it plots a graph that shows how well each model performs. This graph has a U-shape, and here's what it means:

On the left side of the U (the simple models), both the training and validation errors are high. This is underfitting because the model is too basic to make good predictions. In the middle of the U, the errors are the lowest. This is the "sweet spot" where the model is just right in terms of complexity.

On the right side of the U (the complex models), the training error becomes very low, but the validation error starts going up. This is overfitting because the model is too complex and starts making bad predictions on new data. In essence, the code shows that finding the right balance in model complexity is crucial. Too simple or too complex models both lead to poor predictions. The goal is to strike the right balance in the middle of the U-shaped curve where the model generalizes well to new, unseen data.



 
