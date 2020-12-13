# mnist-DCGAN
Generate handwritten numbers from MNIST data with gaussian noise- using DCGAN method

The productive layer contains a CNN with inverted torsional layers. In fact, in this section, upsampling is performed, which means that it increases and creates features and samples. This is done from the heart of the noise.
In the case of the story divider, the opposite is true. According to (Figure 1) in this section, a typical CNN is used to point out that there is no pooling or fully-connected. In this section, downsampling is done from a lot of input data after a lot of filtering. In fact, it removes unimportant data and highlights important features.
All models use 128 -SGD and 128-mini-bachs. Also, all weights are made randomly with a standard deviation of 0.02 to zero. The slope of the LEAKY RELU function is assumed to be 0.2. Adam is also used instead of momentum to speed up learning. Regarding the learning coefficient, 0.0002 was used, which is a much lower value than 0.001. The B1 coefficient used in the momentum section was changed from 0.9 to 0.5 because the previous coefficient caused instability in the network.

