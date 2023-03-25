# MarineVision
This project is a web application that takes an image as input, uses a pretrained Keras model to detect ships in the image, and outputs the result. The web application is built on Flask and can be easily deployed on a server.

# Data
The dataset used in this project is a collection of satellite images of sizes 768x768 pixels. Each image is accompanied by a label indicating the presence or absence of a ship in the image. The dataset is not included in the repository due to its large size, but can be downloaded from the following link: https://www.kaggle.com/competitions/airbus-ship-detection/data

# Demo
https://user-images.githubusercontent.com/100841251/227709792-2f7ffa55-8e96-432d-9ed6-cfce8911d20b.mp4

# Model
The model used in this project is a convolutional neural network (CNN) trained on the dataset described in the Data section. The model architecture consists of several convolutional and pooling layers, followed by a series of fully connected layers. The model is trained using the binary cross-entropy loss function and the Adam optimizer.
# License
This project is licensed under the BSD 3-Clause License. See the LICENSE file for details.
