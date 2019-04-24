# CIFAR 100

https://www.cs.toronto.edu/~kriz/cifar.html

#### Code

```python
from keras.datasets import cifar100
(x_train, y_train), (x_test, y_test) = cifar100.load_data(label_mode='fine')
```

#### Overview

There are 50,000 train and 10,000 test **color** images across **100** different categories.

You are trying to get the highest accuracy on the **test data set**.

#### Instructions

- Load Data
- Display the first 10 images and their labels (matplotlib)
- Scale/Transform
- Build CNN model (try various architectures)
- Plot loss, train accuracy, validation accuracy
- Compute accuracy for the test set

#### Fin

