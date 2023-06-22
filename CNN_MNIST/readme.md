## **Convolutional Neural Networks**
Convolutional neural network (CNN) is a class of deep neural network and is commonly applied for processing structured arrays of data such as images. CNN is widely used in computer vision. They have many applications in image and video recognition, image classification, natural language processing, etc.

A basic convolutional neural network includes an input layer, hidden layers, and an output layer.

- The input is a tensor of shape (number of images) × (image height) × (image width) × (number of channels)
- Hidden layers are located between the input and the output layer. They include convolutional layers and are followed by other layers such as pooling layers, normalization layers, and fully connected layers.
- The output layer is the last layer of the network that produces the final result of the program.
![CNN](https://github.com/KhuyenLE-maths/Medium_blogs/assets/69978820/c0f51c25-0904-43b4-bcdf-b8ce1354dd3c)

The detailed introduction to the CNN model, as well as the inside operations, are presented in [my blog](https://medium.com/mlearning-ai/convolutional-neural-networks-3f00c165c9d9).

In this [notebook](https://github.com/KhuyenLE-maths/Medium_blogs/blob/main/CNN_MNIST/CNN_MNIST.ipynb), we are going to build a basic CNN model to classify MNIST handwritten digit images.

