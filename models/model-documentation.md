# Model Documentation

## Simple, dense model

### Idea
Try out the simplest possible model

### Design
A model composed of two dense layers with an arbitrarily chosen number of 10 neurons feed into a single output layer of one neuron.
Activation was set to ReLU since that worked for an unrelated showcase.
The model was trained on diesel price, wind speed and cars per hour for 10 epochs with a batch size of 64.

### Model file
[SimpleModelling.ipynb](../SimpleModelling.ipynb)

### Outcome
The model is able to predict with an accuracy of 80% the NO2 data of 2019.