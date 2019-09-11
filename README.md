# Keras-FB-Merged-Forecast

This forecast script trains data with the Facebook Prophet Library, creating a forecast
of the training data (specific to license usage). Then the residuals calculated from the 
FB Prophet training are passed as data points to train a new Keras model, which fine tunes 
the predictions FB Prophet produces, creating a more accurate forecast model.
