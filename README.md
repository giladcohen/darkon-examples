# darkon-examples
Examples and use cases for darkon

## Install python package
pip install darkon

## mnist-cnn
Influence score calculation example
It first trains CNN model for MNIST data, and calculate influence score to find most helpful and harmful training samples.
Then, retrain the model after removing 100 most helpful training samples and 100 most harmful training samples, respectively.

## With cifar10-resnet
- [example code](https://github.com/darkonhub/darkon-examples/blob/master/cifar10-resnet/influence_cifar10_resnet.ipynb)
- dataset: [cifar10](https://www.cs.toronto.edu/~kriz/cifar.html)
- network: [resnet110](https://github.com/wenxinxu/resnet-in-tensorflow)