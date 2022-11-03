# Churn_model_prediction

This is a simple ANN model for churn_model_prediction.

I have extracted the data from uci

I have used some feature engineering techinques like looking for null values, one hot encoding categorical variables, removed unwanted columns.

The data is then split into train, validation, and test.

The data got scaled with Standard scaler technique and taken for modelling.

I have used ANN model with two hidden layers. This is a Binary-Classification problem so ReLU activation function was used in input layer and hidden layers, whereas the output layer contain Sigmoid activation function.

I have Adam Optimizer as it is best among other optimizers.

Finally the scaled model and ANN model was pickled and stored for future use.
