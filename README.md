# What is this repository about?

This repository is intended to be an informal, and introductory guide to building a convolutional neural network variational autoencoder (or CNN VAE, because who has time to say all of that every time!!!!) for regression purposes (rather than classification) using the R Keras package.

Throughout my time learning to build and fit CNN VAE with R Keras, I struggled to find many examples or tutorials online specifically written in R. Understandably, most examples were written in Python, and while it is relatively easy to convert the Python syntax defining models to R, it is still somewhat difficult if you have never before seen the relevant R syntax of what you are converting. I've put together this fairly straight-forward example in the hope that it will be helpful to anyone looking to build their own CNN VAE. :)

# Credit where credit is due

During my search I did find a very good R Keras tutorial for a VAE built with dense (fully-connected) layers, written by Daniel Falbel, JJ Allaire, and François Chollet. I have taken their model, and tweaked it by changing some of the layers from dense to convolutional, as well as adjusting a few other things to improve the fit under the new layer structure. I also changed cross-entropy component of the loss function to a mean squared error function, since I am focussed on regression applications. The VAE tutorial can be found at:

https://keras.rstudio.com/articles/examples/variational_autoencoder.html

I highly recommend starting with the above tutorial before looking through mine. 

# The CNN VAE

To be completed... 

