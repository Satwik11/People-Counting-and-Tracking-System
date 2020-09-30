# People-Counting-and-Tracking-System

In this project, the goal is to do OpenCV analysis using algorithms such as Mobile net, SSD(Single Shot Detector), and DNN(Deep Neural Network) for people detection and tracking. This model can be used to count the people entering and exiting the Restaurants or Shopping malls. Then created a frontend using flask.

## What is Object Detection
In Object Detection, we categorize an image and identify where does an object resides in an image. For this, we have to obtain the bounding box i.e (x, y)-coordinates of an image. Frame detection is considered as a regression problem. That makes it easy to understand.Single Shot detection is one of the methods of Object Detection

## Various Object Detection Methods
1.Faster RCNN
2.Single-shot detection
3.You look only once (YOLO)

![Test Image 1](https://honingds.com/wp-content/uploads/2020/01/image-result-for-object-detection.jpeg)

### Single Shot object detection or SSD takes one single shot to detect multiple objects within the image. As you can see in the above image we are detecting coffee, iPhone, notebook, laptop and glasses at the same time.

It composes of two parts
1.Extract feature maps, and
2.Apply convolution filter to detect objects

## Why use MobileNet in SSD
Resnet or VGG or alexnet has a large network size and it increases the no of computation whereas in Mobilenet there is a simple architecture consisting of a 3×3 depthwise convolution followed by a 1×1 pointwise convolution.


