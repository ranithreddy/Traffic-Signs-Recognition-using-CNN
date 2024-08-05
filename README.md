# Traffic-Signs-Recognition-using-CNN

This is my second project in college traffic sign recognition using the CNN algorithm.

**#What is Traffic Signs Recognition?**

Traffic Sign Recognition (TSR) is an important part of the driver support functions needed to make intelligent vehicles. The automatic system for classification of traffic signs is a critical task of an Advanced Driver Assistance Systems (ADAS) and a fundamental technique utilized as integral part to the various vehicles. The recognizable features of a traffic image are utilized for their classification. Traffic signs are designed in such a way that they contain specific shapes and colors, with some text and some symbols with high contrast to the background.

**The Dataset of Python Project**
For this project, we are using the public dataset available at Kaggle: [Traffic Signs Dataset](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign/code)




**Dataset structure**

The dataset are divided as follow :

    34799 images for the training set.
    4410 images for the validation set.
    12630 images for the test set.

The images' shapes are (32, 32, 3) (RGB).

The training set archive is structured as follows :

    One directoy per class
    Each directory contains one Comma Separated Value (CSV) file with annotations (GT-ClassID.csv), as well as the training images.
    Training images are grouped by tracks.
    Each tracks contains 30 images of one single physical traffic sign.


**Image format**


    The images contain one traffic sign each.
    Images contain a border of 10% around the actual traffic sign (cropped to at least 5 pixels) to allow for edge-based approaches.
    They are stored in Pickle5 format (PPM format).

The 43 different classes are :

    0, Speed limit (20km/h)
    1, Speed limit (30km/h)
    2, Speed limit (50km/h)
    3, Speed limit (60km/h)
    4, Speed limit (70km/h)
    5, Speed limit (80km/h)
    6, End of speed limit (80km/h)
    7, Speed limit (100km/h)
    8, Speed limit (120km/h)
    9, No passing
    10, No passing for vehicles over 3.5 metric tons
    11, Right-of-way at the next intersection
    12, Priority road
    13, Yield
    14, Stop
    15, No vehicles
    16, Vehicles over 3.5 metric tons prohibited
    17, No entry
    18, General caution
    19, Dangerous curve to the left
    20, Dangerous curve to the right
    21, Double curve
    22, Bumpy road
    23, Slippery road
    24, Road narrows on the right
    25, Road work
    26, Traffic signals
    27, Pedestrians
    28, Children crossing
    29, Bicycles crossing
    30, Beware of ice/snow
    31, Wild animals crossing
    32, End of all speed and passing limits
    33, Turn right ahead
    34, Turn left ahead
    35, Ahead only
    36, Go straight or right
    37, Go straight or left
    38, Keep right
    39, Keep left
    40, Roundabout mandatory
    41, End of no passing
    42, End of no passing by vehicles over 3.5 metric tons


**Installation**
    python main.py


Disadvantages

    Static image processing, this means parameters must be updated for each video with different lighting conditions
    The accuracy of the detection phase is not high, still, miss signs or detect wrong areas.
    The dataset is a little bit overfitting for classification phase.

