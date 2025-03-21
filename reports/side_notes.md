# Side Notes

The mean (average) of a data set is found by adding all numbers in the data set and then dividing by the number of values in the set. The median is the middle value when a data set is ordered from least to greatest. The mode is the number that occurs most often in a data set.

---

The Any type docstring states that object is a subclass of Any and vice-versa:

> > > import typing
> > > print(typing.Any.**doc**)
> > > Special type indicating an unconstrained type.

    - Any object is an instance of Any.
    - Any class is a subclass of Any.
    - As a special case, Any and object are subclasses of each other.

However, a proper typechecker (one that goes beyond isinstance() checks, and which inspects how the object is actually used in the function) can readily object to object where Any is always accepted.

---

Gradient descent is an optimization algorithm which is commonly-used to train machine learning models and neural networks. It trains machine learning models by minimizing errors between predicted and actual results.

---

The activation function in a neural network processes the input from an artificial neuron to produce the desired output. Activation functions are used to introduce non-linearity and enable the network to approximate complex functions, while loss functions are used to provide feedback to the network during training, helping it adjust its weights and biases to minimize the error.

---

In deep learning, an optimizer is a crucial element that fine-tunes a neural network's parameters during training. Its primary role is to minimize the model's error or loss function, enhancing performance.
