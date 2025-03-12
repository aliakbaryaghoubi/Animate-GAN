# Animate-GAN
IMT Deep Learning Course Project 3

Generative Adversarial Networks (GANs) are models that generate new examples by discovering patterns in the training data. A GAN model consists of two interconnected neural network models: the generator and the discriminator. The generator attempts to fool the discriminator by generating fake output data. It takes noise (with a normal distribution) as input and is continuously updated based on feedback from the discriminator during each epoch of training. On the other hand, the discriminator's task is to distinguish fake images from real ones by receiving both as input for training. These two models update each other iteratively until they reach a point where the discriminator is no longer able to differentiate fake images from real ones.

The flowchart below illustrates the GAN computation process.

![image.png](attachment:f59ed53e-8e87-4406-bca8-0d8705bac147.png)

In this notebook, the task is to generate a number of animate characters images by training a GAN model on the related dataset. The dataset contains 63,565 images of animate characters.
