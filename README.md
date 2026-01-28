# Fashion-MNIST-Image-Classification
## Google Colab Link:[https://colab.research.google.com/drive/18jmmxy0-fDmjAveio4MyUdJA6B3CL5N9?usp=sharing]
### Questions:
_1. What is the Fashion MNIST dataset?_
**The Fashion MNIST dataset is a collection of grayscale images of clothing items such as shirts, shoes, and bags. Each image is 28×28 pixels and belongs to one of 10 different classes. It is commonly used for training and testing machine learning models.**

_2. Why do we normalize image pixel values before training?_
**Image pixel values are normalized to make training faster and more stable. Keeping the values between 0 and 1 helps the model learn better and improves performance.**

_3. List the layers used in the neural network and their functions._
**Flatten layer – converts the image into a one-dimensional array
Dense (hidden) layer – learns patterns and features from the data
Output layer – gives the final prediction for each class**

_4. What does an epoch mean in model training?_
**An epoch means one complete pass of the training data through the neural network.**

_5. Compare the predicted label and actual label for the first test image._
**The actual label is the true class of the image, while the predicted label is the class chosen by the model. If both labels are the same, the prediction is correct.**

_6. What could be done to improve the model’s accuracy?_
**The model’s accuracy can be improved by adding more layers, increasing the number of epochs, using a CNN, or tuning the model’s parameters.**
