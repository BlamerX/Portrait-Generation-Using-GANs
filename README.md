
# Portraits Generation Using GANs

![](https://i.pinimg.com/736x/cf/fa/57/cffa57d6bb324f84e9eecdb340523ae0.jpg)

## About Dataset

I have used this dataset as It has only 10k+ images. This was a Subset of the [Oiginal dataset](https://academictorrents.com/details/1d154cde2fab9ec8039becd03d9bb877614d351b) also on [Kaggle dataset](https://www.kaggle.com/datasets/ipythonx/wikiart-gangogh-creating-art-gan) but as i had to train for long and the time constraint i had to go with this as it is a really great dataset.

A collection of online art home gallery



## Problem Statement

The objective is to train a model capable of generating realistic and diverse art portraits based on a given dataset of art images. The model should consist of a generator network, responsible for generating images from random noise, and a discriminator network, responsible for distinguishing between real and generated images. The goal is to train the GAN model such that the generator learns to produce high-quality art portraits that are indistinguishable from real ones, while the discriminator learns to accurately differentiate between real and generated images. The training process involves optimizing both the generator and discriminator networks in an adversarial manner, where the generator aims to fool the discriminator, and the discriminator aims to correctly classify real and fake images. The success of the model will be evaluated based on the visual quality of the generated art portraits and the convergence of the training process.

## Result

![](generated_images.gif)
