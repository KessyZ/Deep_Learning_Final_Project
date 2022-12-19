# Deep_Learning_Final_Project
Image colorization is a technique to add color to black and white photos, which is widely used in old photo restoration, medical image processing, etc. Previously, image colorization is tackled by supervised learning such as classification and regression. However, Phillip[1] proposed a conditional adversarial network consisting of a generator and a discriminator which can solve the problem by unsupervised learning. In this project, we are going to reproduce and fine-tune the network and compare different results to find the optimal network.
We plan to use COCO dataset. Due to the high volume of pictures in dataset, we are going to randomly select 16000 of them as training samples and 4000 as testing samples.
We are going to build a conditional GAN which consists of a U-Net generator and a discriminator. For U-Net, we will use ResNet18 as the backbone.
The total number of trainable parameters would be about 40M.
