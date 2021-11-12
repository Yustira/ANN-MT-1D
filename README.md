# ANN MT 1D

This study aims to construct the ANN model to estimate 
the resistivity distribution of the earth’s subsurface and its implementation in 1D
inversion of the magnetotelluric data. The network is trained on synthetic data with
Gaussian noise using forecasting and deep learning approaches. The network is
able to adapt to the training data in less than a minute. After training, the ANN
model is able to reproduce forward response with an accuracy similar to the error
level of the regular inversion. The trained network was used to estimate forward
response in the inversion of 1D magnetotelluric data for the example of synthetic
model of the geothermal system. The inversion results show the resistivity distri-
bution of the earth’s subsurface directly from magnetotelluric data in a single step
without any iterations. This procedure simplifies the magnetotelluric inversion pro-
cess and allows to estimate the resistivity subsurface from different magnetotelluric
data.
