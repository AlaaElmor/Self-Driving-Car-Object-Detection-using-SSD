# Self-Driving Car Object Detection using SSD
The SSD (Single Shot Multibox Detector) is a popular object detection model that is widely used in the field of computer vision. It is a neural network architecture that is designed to detect objects in images and videos with high accuracy and speed.

The SSD model works by dividing an input image into a grid of cells, and each cell is responsible for detecting objects that are located within its boundaries. The model predicts multiple bounding boxes (or "multiboxes") for each cell, each with a different size and aspect ratio, and it also predicts the probability of each box containing an object of interest.

During training, the SSD model learns to adjust the size and location of the multiboxes to accurately fit the objects in the image. It also learns to classify the objects into different classes (such as "car", "truck", "pedestrian", etc.), based on the features of the object within the multibox.

Compared to other object detection models, the SSD is known for its fast inference speed and high accuracy, making it a popular choice for applications such as self-driving cars, surveillance systems, and robotics.

In your code, you have used the SSD model to detect objects for the five classes of objects you are interested in (cars, trucks, pedestrians, bicyclists, and traffic lights).

![__results___22_0](https://user-images.githubusercontent.com/77681678/235401182-39af36e1-ac79-4c30-918b-d865342abce6.png)

# Dataset: https://www.kaggle.com/datasets/alincijov/self-driving-cars
