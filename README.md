# Face Generation using DCGAN

In this project, I define and train a DCGAN on a dataset of faces in order to get a generator network to generate new images of faces that look as realistic as possible!

## Installation

Download and run the notebook (PyTorch).
The model is trained using pre-processed CelebA dataset of faces (64x64x3 images).

The dataset can be downloaded from https://s3.amazonaws.com/video.udacity-data.com/topher/2018/November/5be7eb6f_processed-celeba-small/processed-celeba-small.zip.

## Content

- Get and pre-process data
- Create DataLoader
- Define the model:
  - Discriminator
  - Generator
  - Initialize weigths
  - Build complete network
- Define Discriminator and Generator losses
- Define Optimizers
- Train the model
- Generate samples from training
