# GAN-Versus-Anime-Faces

Abstract


In the computer vision domain, generative adversarial network (GAN) is a symbolic machine learning approach to generate artificial images. To achieve it, GAN usually contains two modules that play a minimax game, a generator that produces fake images and a discriminator that classifies the images as either real or fake.1 Since Goodfellow (2014) set up the frame of GAN, many extended versions of GAN have been developed rapidly for various applications in different domains. In this project, we compare two GANS (StyleGANs and DCGANs), implement them on an animate dataset, and discuss their results of image synthesis.

Dataset


The dataset we are using is Anime Face Dataset on Kaggle.2 It was created by Spencer Churchill. The dataset contains 63,632 animate faces without labels. The typical size of an image is between 90×90 and 120×120. We also reduced the dataset to 19,000 images in some of our models.
