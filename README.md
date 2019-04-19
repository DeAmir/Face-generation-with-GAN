# Generating faces with Generative Adversarial Network (GAN)
This is a keras implementation of a face generating GAN.

## The data
I used the CelebFaces dataset to train the network.\
Please check out the dataset on kaggle, [here](https://www.kaggle.com/jessicali9530/celeba-dataset).\
In order for the code to run and fetch the dataset, you have to put your kaggle api key.\

## The models
In the notebook, there are several models. Some are better, and some are worse.\
They are orginized in the following syntax:
- If they contain 1D in the name, the take a 1D input (a vector). If they contain a 2D in the name, they take 2D input (a matrix)
- If they contain "conv" it means it a convolutional(the convolutional nets work worse then the regular ones).

## Notice
Sometimes the discriminator takes over the generator, thus making the generator produce less realistic images.\
Feel free to change the learning rate on of the optimizers (works for me), or add some kind of normalization.\
Also, if you choose to load the images with gray scale, you have to change the **channels** variable accordingly.
