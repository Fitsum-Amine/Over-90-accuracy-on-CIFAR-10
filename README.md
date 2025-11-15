# Over-90-accuracy-on-CIFAR-10
I built a model with 5 convolutional layers, incorporating a residual connection after every 2 layers. Unlike ResNet18, which was originally designed for ImageNet (224x224) and uses strided convolution for downsampling the feature maps at the beginning of each stage, we decide to maintain the original dimensions of the images in CIFAR-10 (32x32).
