# Generative Models

-----------------

### Short intro about GANs

> GANs are a framework for teaching a DL model to capture the training data’s distribution so we can generate new data from that same distribution. GANs were invented by Ian Goodfellow in 2014 and first described in the paper Generative Adversarial Nets. They are made of two distinct models, a generator and a discriminator. The job of the generator is to spawn ‘fake’ images that look like the training images. The job of the discriminator is to look at an image and output whether or not it is a real training image or a fake image from the generator. During training, the generator is constantly trying to outsmart the discriminator by generating better and better fakes, while the discriminator is working to become a better detective and correctly classify the real and fake images. 

* **Models**

  1) Variational Autoencoder
  2) Deep Convolutional GAN (DCGAN)

<br>


1) VAE - Mnist
    * [notebook](https://nbviewer.jupyter.org/github/veb-101/Generative_Models/blob/master/Variational_autoencoder_MNIST/Variational_autoencoder_pytorch.ipynb)
    * Example generation
        ![VAE_mnist](./Variational_autoencoder_MNIST/generation.gif)


2) VAE - Labelled Faces in the wild dataset
   * [notebook](https://nbviewer.jupyter.org/github/veb-101/Generative_Models/blob/master/Variational_autoencoder_LFW/generate-celebrity-faces-vae.ipynb)
   * Not much success in generation
  
3) DCGAN - MNIST
    * [notebook](https://nbviewer.jupyter.org/github/veb-101/Generative_Models/blob/master/DCGAN_Mnist/DCGAN_MNIST.ipynb)
    * Example Generation: View Notebook
    
4) DCGAN - CELEBA dataset
 *  [notebook](https://nbviewer.jupyter.org/github/veb-101/Generative_Models/blob/master/DC_GAN_CelebA/DCGAN_CelebA_dataset.ipynb)
 *  Example Generation
  ![dcgan_celeba](./DC_GAN_CelebA/celebrity.gif)

5) DCGAN - Anime faces dataset
   * [notebook](https://nbviewer.jupyter.org/github/veb-101/Generative_Models/blob/master/DCGAN_Anime_faces/dcgan-anime-faces.ipynb)
   * Example Generation
    ![dcgan_anime](./DCGAN_Anime_faces\generation.gif)


* **PS:** GANs are harder to train than I imagined.
* These examples generation can be better, you are very welcome to take my started code and add on it.

