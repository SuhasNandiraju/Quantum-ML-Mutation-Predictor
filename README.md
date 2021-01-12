# Quantum-ML-Mutation-Predictor


This project uses Quantum-hybrid Machine Learning to predict genetic mutations in viruses.

First, we train a Quantum-hybrid Variational Autoencoder to encode and decode the data. 
Then, we train a Quantum-hybrid LSTM time series predictor on the encoded and vectorized data.
Then, the make and decode our predictions using decoded trained in the QVAE.

Currently, the model achieves an accuracy of 98.5%, with a median error of 8 from the 566 amino acids present in the sample data points


This project would be useful for preemptive vaccine synthesis, which would cut down the deaths and total infections of seasonal diseases by having a vaccine prepared for unknown mutations.

Graphs:

![alt text](https://github.com/SuhasNandiraju/Quantum-ML-Mutation-Predictor/blob/master/Screen Shot 2021-01-11 at 6.24.17 PM.png?raw=true)

