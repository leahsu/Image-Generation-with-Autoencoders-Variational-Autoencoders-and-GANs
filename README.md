# Image-Generation-with-Autoencoders-Variational-Autoencoders-and-GANs

## Abstract
This Jupyter Notebook is for applying Autoencoders (AEs), Variational Autoencoders (VAEs) and Generative Adversarial Networks (GANs) to a Pokémon image dataset. 

The dataset source is from [Kaggle](https://www.kaggle.com/vishalsubbiah/pokemon-images-and-types) which contains 809 images along with their types (primary and secondary) as a .csv file. 

In this notebook, it will implement Autoencoders (AEs), Variational Autoencoders (VAEs) and Generative Adversarial Networks (GANs) model to generate fake images which do not exist in the original dataset. The image generatin will be stored in the ouptput file.

### Autoencoders (AE)
Autoencoders are neural networks that learn to efficiently compress and encode data then learn to reconstruct the data back from the reduced encoded representation to a representation that is as close to the original input as possible. Therefore, autoencoders reduce the dimentsionality of the input data i.e. reducing the number of features that describe input data.
Since autoencoders encode the input data and reconstruct the original input from encoded representation, they learn the identity function in an unspervised manner.

### Variational Autoencoders (VAE)
Variational Autoencoder is an autoencoder whose training is regularized to avoid overfitting and ensure that the latent space has good properties that enable generative process. The idea is instead of mapping the input into a fixed vector, we want to map it into a distribution. In other words, the encoder outputs two vectors of size nn, a vector of means μ, and another vector of standard variations σ.

### Generative Adversarial Networks (GAN)
A generative adversarial network is a machine learning (ML) model in which two neural networks compete with each other to become more accurate in their predictions. GANs typically run unsupervised and use a cooperative zero-sum game framework to learn.
The two neural networks that make up a GAN are referred to as the generator and the discriminator. The generator is a convolutional neural network and the discriminator is a deconvolutional neural network. The goal of the generator is to artificially manufacture outputs that could easily be mistaken for real data. The goal of the discriminator is to identify which outputs it receives have been artificially created.
