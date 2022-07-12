# GAN-Versus-Anime-Faces

Abstract


In the computer vision domain, generative adversarial network (GAN) is a symbolic machine learning approach to generate artificial images. To achieve it, GAN usually contains two modules that play a minimax game, a generator that produces fake images and a discriminator that classifies the images as either real or fake.1 Since Goodfellow (2014) set up the frame of GAN, many extended versions of GAN have been developed rapidly for various applications in different domains. In this project, we compare two GANS (StyleGANs and DCGANs), implement them on an animate dataset, and discuss their results of image synthesis.

Dataset


The dataset we are using is Anime Face Dataset on Kaggle.2 It was created by Spencer Churchill. The dataset contains 63,632 animate faces without labels. The typical size of an image is between 90×90 and 120×120. We also reduced the dataset to 19,000 images in some of our models.

## Paper
<img src="https://github.com/eddyliao-30/GAN-Versus-Anime-Faces/blob/main/Paper%20Images/Chenxi%20%26%20Minh%20%26%20ShengKai%20-%20GAN%20Versus-Anime%20Faces-01.png">
<img src="https://github.com/eddyliao-30/GAN-Versus-Anime-Faces/blob/main/Paper%20Images/Chenxi%20%26%20Minh%20%26%20ShengKai%20-%20GAN%20Versus-Anime%20Faces-02.png">
<img src="https://github.com/eddyliao-30/GAN-Versus-Anime-Faces/blob/main/Paper%20Images/Chenxi%20%26%20Minh%20%26%20ShengKai%20-%20GAN%20Versus-Anime%20Faces-03.png">
<img src="https://github.com/eddyliao-30/GAN-Versus-Anime-Faces/blob/main/Paper%20Images/Chenxi%20%26%20Minh%20%26%20ShengKai%20-%20GAN%20Versus-Anime%20Faces-04.png">
<img src="https://github.com/eddyliao-30/GAN-Versus-Anime-Faces/blob/main/Paper%20Images/Chenxi%20%26%20Minh%20%26%20ShengKai%20-%20GAN%20Versus-Anime%20Faces-05.png">
<img src="https://github.com/eddyliao-30/GAN-Versus-Anime-Faces/blob/main/Paper%20Images/Chenxi%20%26%20Minh%20%26%20ShengKai%20-%20GAN%20Versus-Anime%20Faces-06.png">
<img src="https://github.com/eddyliao-30/GAN-Versus-Anime-Faces/blob/main/Paper%20Images/Chenxi%20%26%20Minh%20%26%20ShengKai%20-%20GAN%20Versus-Anime%20Faces-07.png">
<img src="https://github.com/eddyliao-30/GAN-Versus-Anime-Faces/blob/main/Paper%20Images/Chenxi%20%26%20Minh%20%26%20ShengKai%20-%20GAN%20Versus-Anime%20Faces-08.png">
<img src="https://github.com/eddyliao-30/GAN-Versus-Anime-Faces/blob/main/Paper%20Images/Chenxi%20%26%20Minh%20%26%20ShengKai%20-%20GAN%20Versus-Anime%20Faces-09.png">
<img src="https://github.com/eddyliao-30/GAN-Versus-Anime-Faces/blob/main/Paper%20Images/Chenxi%20%26%20Minh%20%26%20ShengKai%20-%20GAN%20Versus-Anime%20Faces-10.png">
<img src="https://github.com/eddyliao-30/GAN-Versus-Anime-Faces/blob/main/Paper%20Images/Chenxi%20%26%20Minh%20%26%20ShengKai%20-%20GAN%20Versus-Anime%20Faces-11.png">
<img src="https://github.com/eddyliao-30/GAN-Versus-Anime-Faces/blob/main/Paper%20Images/Chenxi%20%26%20Minh%20%26%20ShengKai%20-%20GAN%20Versus-Anime%20Faces-12.png">
<img src="https://github.com/eddyliao-30/GAN-Versus-Anime-Faces/blob/main/Paper%20Images/Chenxi%20%26%20Minh%20%26%20ShengKai%20-%20GAN%20Versus-Anime%20Faces-13.png">
<img src="https://github.com/eddyliao-30/GAN-Versus-Anime-Faces/blob/main/Paper%20Images/Chenxi%20%26%20Minh%20%26%20ShengKai%20-%20GAN%20Versus-Anime%20Faces-14.png">
