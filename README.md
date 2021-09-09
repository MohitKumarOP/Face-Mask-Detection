# Face-Mask-Detection
In the times of Corona Pandemic when wearing masks has become very necessary for our safety as well as the safety of others, I have created a project which can detect and confirm if a person is wearing a mask or not with up to 99% accuracy. This was a very challenging project as it is an outcome of more than three different domains combined. These different domains are:

Machine Learning:

Under this domain, the backbone of the project was created. Using ML and neural net model namely CNN, I worked on creating a model which can take an image as input and predict if the person in image is wearing a mask or not.

Deep Learning:

This domain worked as a bridge. Various deep learning frameworks and libraries such as Tensorflow, Keras, N5PY were used to load the ML model and run it in real time in synchronization with Computer Vision.

Computer Vision

So, this is the most exciting part of this project because here we are able to see the execution of all the work done on backend. I used OpenCV library to capture video in real time which is then through the Deep Learning bridge is sent to the ML and CNN model where it is compared to the previous data and then the model predicts if the person is wearing a mask or not
