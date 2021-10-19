
# import stuff and what not idk
import tensorflow as tf
import numpy as np
from tensorflow import keras
import matplotlin.pyplot as plt


# pre-defined dataset
fashion_mnist = keras.datasets.fashion_mnist

# extract data and what not
(train_images, train_labels), (test_images, test_labels) = fashion_mnist.load_data()

# show le data
plt.imshow(train_images[0], cmap='grey', vmin=0, vmax=255)
plt.show()
# ...

# the real shit happens now.
model = keras.Sequential([
