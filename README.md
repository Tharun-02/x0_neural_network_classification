# x0_neural_network_classification

[![Python Version](https://img.shields.io/badge/language-python3.6-yellow.svg)](https://www.python.org/downloads/) [![Tensorflow Verion](https://img.shields.io/badge/language-tensorflow2.12-teal.svg)](https://www.tensorflow.org/install)



This repository is a project which I created to learn about of TensorFlow, Deep Learning, Neural Network [Tensorflow].

The main objective of the project is to Create a Neural Network Model which can solve the binary classification problem based on Deep Neural Networks.
The Dataset is generated using **Scikit-learn's** `Make_moon()` function.

Just a simple project to get started with Tensorflow and Neural Network.

## Requirements

- Python 3.10.11
- Tensorflow 2.12.0
- Sklearn 1.2.2
- Numpy 1.22.4
- Matplotlib: 3.7.1
- Pandas: 1.5.3

## Dataset
Here's the DataFrame of the Dataset:
> `Pandas.DataFrame()`

Here in this project, I've used moons dataset from Scikit-learn's `sklearn.dataset.make_moons` which looks like cresent shaped formed with lot of small circles which we can adjust the values.

## Visualizing the Data
```python
import matplotlib.pyplot as plt
plt.scatter(X[:,0], X[:,1], c=y,cmap=plt.cm.RdYlBu)
```
![plt_moons](https://github.com/Tharun-02/x0_neural_network_classification/assets/83574493/8a9c353d-b292-474a-8b3a-9db819a8feaa)

But it's not the only dataset for getting started on binary classification, Scikit-learn has lot of data generator functions like the one I've used in this project,
[***Scikit-learn Data/Sample Generators***](https://scikit-learn.org/stable/modules/classes.html#module-sklearn.datasets)

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

