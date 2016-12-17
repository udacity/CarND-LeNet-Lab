# CarND-LeNet-Lab
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

![LeNet-5 Architecture](lenet.png)
Implement the LeNet-5 deep neural network model.

### Dependencies
This lab requires:

* [TensorFlow](https://www.tensorflow.org/)

Use [Anaconda](https://www.continuum.io/downloads) to install the dependencies:

1. `conda env create -f environment.yml`
2. `source activate CarND-LeNet-Lab`

### GPU
If you have access to an NVIDIA GPU, you can accelerate the training of your network by using TensorFlow on a GPU.

1. Install the core dependencies (see above)
2. Install [CUDA](https://developer.nvidia.com/cuda-downloads)
3. Install [cuDNN](https://developer.nvidia.com/cudnn)
4. Install TensorFlow with GPU support: `pip install tensorflow-gpu`
