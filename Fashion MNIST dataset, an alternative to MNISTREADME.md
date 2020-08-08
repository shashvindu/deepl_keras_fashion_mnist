# deepl_keras_fashion_mnist
# Fashion MNIST dataset, an alternative to MNIST
Loads the Fashion-MNIST dataset.

This is a dataset of 60,000 28x28 grayscale images of 10 fashion categories, along with a test set of 10,000 images. This dataset can be used as a drop-in replacement for MNIST. The class labels are:
abel	Description
0	T-shirt/top
1	Trouser
2	Pullover
3	Dress
4	Coat
5	Sandal
6	Shirt
7	Sneaker
8	Bag
9	Ankle boot
Returns

Tuple of Numpy arrays: (x_train, y_train), (x_test, y_test).

x_train, x_test: uint8 arrays of grayscale image data with shape (num_samples, 28, 28).

y_train, y_test: uint8 arrays of labels (integers in range 0-9) with shape (num_samples,).

License: The copyright for Fashion-MNIST is held by Zalando SE. Fashion-MNIST is licensed under the MIT license.
https://keras.io/api/datasets/fashion_mnist/
