## Dog Breeds Project

This project explores using a convolutional neural network ([CNN](https://en.wikipedia.org/wiki/Convolutional_neural_network)) to classify different dog breeds using dog images. During prediction if a human image is passed to the model it will attempt to predict what type of dog the person looks like. Transfer learning is used to start with a pre-trained model, specifically the [ResNet-50](https://github.com/KaimingHe/deep-residual-networks) image classification model which has been trained on [ImageNet](http://www.image-net.org/). The [VGG-16](http://www.robots.ox.ac.uk/~vgg/research/very_deep/) image classification model is also used for transfer learning as an intermediate step.

The data used in this project can be found below:

* [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip) - Unzip into root of the project. Images should be in the dogImages folder.
* [human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip) - Unzip into root of the project. Images should be in the lfw folder.
* [VGG-16 bottleneck features](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogVGG16Data.npz) - Place file in bottleneck_features folder.

This project is using Python 3 and needs the following libraries:

* keras
* TensorFlow
* tqdm
* opencv-python
* numpy
* scikit-learn
* matplotlib
* jupyter notebook

These can be installed using pip or conda if using [Anaconda](https://www.continuum.io/downloads).

The project is implemented in a Jupyter notebook and can be run using the following from a terminal:

```jupyter notebook dog_app.ipynb```
