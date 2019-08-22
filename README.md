# cGAN for Data Augmentation

The main idea is to generate new and realistic synthetic data based on labels. GANs are excellent at generating realistic data. We can condition this generation by using [Conditional Generative Adversarial Networks](https://arxiv.org/abs/1411.1784)

Refer to [Jupyter notebook](https://jscriptcoder.github.io/data-augmentation-using-cgan/data-augmentation-using-cGAN.html) to see the different architectures for Discriminator and Generator model, as well as how they're chained together in an assembly-line sort of way where the input of the GAN is the Generator's input. The Generator's output becomes the input of the Discriminator, which outputs the validity of the features (output of the GAN).

I wrote about it in [Medium](https://medium.com/@jscriptcoder/data-augmentation-using-conditional-gan-cgan-d5e8d33ad032)
