Assignment_2_0446171

Constructing a Neural Network for Handwritten Digit Recognition using TensorFlow

Recognition of handwriting has two basic applications in both Machine Learning and Computer Vision. The research project that I studied in this study is the one concerning the creation of an artificial neural network which can efficiently recognize handwritten characters and TensorFlow develops it. The MNIST data set (5000 training samples of handwriting digits) each image is represented by a 20x20 square grid in grayscale, each pixel is converted into its own floating point number and trained along with the pixel grid whose image is represented by the original grayscaled image. The pixel energy is then transformed into a 400-dimensional vector. Inthe data matrix X was written in the first row.

An multi-output softmax function is involved in a multiclass neural network that provides N outputs, one of which is chosen as the predicted answer. Vector z is the result of linear function applied in the output layer and is passed in softmax function. Receiving by softmax the outcomes are tightly couped in between 0 and 1 and their sum is 1, so the probabilities are determined. Softmax function shows an outstanding capacity to accommodate bigger data volume with the more inputs.

The Deep Neural Network that I created for the task of recognizing of 10 handwritten digits (multiclass classification task) consisted of two dense layers of Rectified Linear Unit (ReLU) activation that were followed by an output layer with a linear activation for the symbol of a digit.

First of all, TensorFlow played an important role in composing the network of neural networks where the levels of input parameters came earlier and subsequent levels of output parameters were specified.

As a result, this article has presented an algorithm of how neural networks are applied to handwritten character recognition with the help of TensorFlow library, and the softmax classifications’ description as a stabilization method during trainings process and also developing a TensorFlow model for hand-written character classification. What follows is then the investigation on other forms of classification methods suited for incorporation into the newly developed neural networks.

Thank you

Aditya Patel
