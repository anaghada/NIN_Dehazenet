# NIN_Dehazenet
Single Image Dehazing is most important field in computer vision and its
been a challenging problem.NIN-Dehazenet is a defogging approach based
on deeplearning.
Add the mlpconv layer to MSCNN(Single Image Dehazing using MultiScale Convolutional Neural Networks) instead of the standard linear convolution layer by adding NIN-Dehazenet to the Network-in-Network structure. This method is known as NIN-DehazeNet. Hence, could get a more
accurate transmission map using NIN-DehazeNet. After that, plug it into
the atmospheric scattering model to get a dehazing image.
Here NIN-Dehazenet estimates the transmission map of single image
by combining Network-in-Network with Multi-Scale Convolution Neural
Network to obtain a fog free image.For that train dataset using RESIDE
dataset with clear,hazy and trans images.Later the model is configured with
UI for predict the output with defogged image with better measures.
