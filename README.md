# Genrating-Handwritten-Digits-using-GAN

Tenserflow-keras implementation of a Generative adversarial Network for generating handwritten digits trianed via MNIST dataset (containing handwritten digits of 28x28 pixel size)
The architecture of the GAN contains a discriminator (trained on actual dataset for real images) and a Generator (which generates images and tries to fool the discriminator)
The output of the discriminator is a sigmoid layer whereas the ouput the Generator is a 28x28 pixel grey scale image fed in the discriminator ( )  
