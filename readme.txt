Project 1:

A Unet is trained on brain MRIs of patients with Alzheimer's disease to segment out the hippocampus. The google colab jupyter notebook file training the neural network on the already
cleaned data is called unet.ipynb. Additionally, the output folder called models of the unet.ipynb can be looked at. It contains traing and validation losses for 10 epochs in a csv file,
aswell as pictures of the predicted hippocampus region for every epoch and the true hippocampus region.

Project 2:

60 minute closing prices of stocks in the sp500 are simulated by first reducing their dimensionality to a vector of size 5 (per stock) with a 1d convolutional autoencoder.
Using a gaussian copula for the dependence structure and their marginal empirical distribution functions the smaller size representations of the stock prices are simulated and then
fed into the decoder part of the autoencoder to produce simulated stock prices. The google colab jupyter notebook autoencoder_adjclose.ipynb contains the whole analysis. 