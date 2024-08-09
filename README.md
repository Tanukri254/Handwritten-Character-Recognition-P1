import tensorflow
from tensorflow import keras
from tensorflow.keras import Sequential
from tensorflow.keras.layers import Dense,Flatten
(X_train,y_train),(X_test,y_test) = keras.datasets.mnist.load_data()
X_test.shape

(10000, 28, 28)
y_train

array([5, 0, 4, ..., 5, 6, 8], dtype=uint8)

import matplotlib.pyplot as plt
plt.imshow(X_train[2])

<matplotlib.image.AxesImage at 0x7f573ed9f790>

