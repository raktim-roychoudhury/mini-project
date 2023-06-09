# mini-project
Designing CNN Architectures for CIFAR-10 Image Data Classification

In our project, we are tasked with designing a modified residual network architecture to classify the CIFAR-10 image dataset. For our model, we decided to adopt the residual block module from MobileNetV2 architecture (Sandler et al. 2019) based on an inverted residual structure where the shortcut connections are between the thin bottleneck layers. We propose a model which includes 17 of these residual blocks, resulting in a final network architecture with 2.6 million parameters. Our empirical results show that this architecture is very robust and achieves a 94.8% accuracy on the CIFAR-10 test set, without any regularization.
