# Generating faces with Generative Adversarial Network (GAN)
This repo contains an implementation of a DCGAN using PyTorch, for creating new faces.\
Here are some faces the model generated (the gray ones are from the older, keras version; the others - from the PyTorch version):\
![Gray scale generated faces](https://raw.githubusercontent.com/LoliamShely/Face-generation-with-GAN/master/example_2.png)
![First colored faces](https://raw.githubusercontent.com/LoliamShely/Face-generation-with-GAN/master/example_1.png)
![The better, PyTorch implementation generation](https://raw.githubusercontent.com/LoliamShely/Face-generation-with-GAN/master/generated.png)
## The Data
I used the CelebFaces dataset to train the network.\
Please check out the dataset on kaggle, [here](https://www.kaggle.com/jessicali9530/celeba-dataset).\
In order for the code to run and fetch the dataset, you have to fill your kaggle api key.

## The Architecture
The both notebooks follows the paper [Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks](https://arxiv.org/abs/1511.06434).

Also note, that this repo also contains a keras implementation of the DCGAN, but the PyTorch version is more formatted.
