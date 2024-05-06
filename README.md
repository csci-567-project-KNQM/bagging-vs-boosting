# CS567 Project - Exploring bagging and boosting

## Jupyter notebooks used to generate results:

To generate results included in the report, please run the following notebooks.

* ```main.ipynb``` and ```main_GPU.ipynb``` in the branch ```Niccolo-Refactor```: Tests
bagging on logistic regression with certain parameters (number of training examples, 
number of base models, regularization strength).

* ```main.ipynb``` in the branch ```ketan/boosting-experiments```: Includes more experiments 
on boosting.

* ```cnn.ipynb``` in the branch ```cnn```: Tests bagging on CNN.

## Other notebooks

These are some of the things we implemented but did not include in the report.

* ```main.ipynb``` in the branch ```ketan/dataset-visualization-knn```: Includes experiments
on bagging with k-NN as the base model using the breast cancer dataset.

* ```cnn.ipynb``` in the branch ```ketan/cnn-gpu-opt```: Adds the option of using GPU 
instead of CPU to train CNNs.

## Datasets

* [Breast Cancer Wisconsin (Diagnostic)](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic)
* [Arrhythmia](https://archive.ics.uci.edu/dataset/5/arrhythmia)
* [DARWIN](https://archive.ics.uci.edu/dataset/732/darwin)
* [MNIST](https://keras.io/2.16/api/datasets/mnist/)
* [Fashion MNIST](https://keras.io/2.16/api/datasets/fashion_mnist/)
* [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html)
([version in Keras library](https://keras.io/2.16/api/datasets/cifar10/))

