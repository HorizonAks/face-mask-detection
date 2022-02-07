# face-mask-detection

In this project, we first download dataset from Kaggle read all the images from the dataset and
train the code on them. Then we use CNN to build a model and then compile it. Later, when we
provide an image from the test data, it compares the features of that face to all the images from
the dataset and returns that the image is with mask or without it. It returns the test image with a
rectangle around the face with label of mask or no mask. It can work on laptop webcam or a video
file provided.

The code is written using OpenCV, Tensorflow and keras. It runs on google Colab or jupyter
notebook. 

#### Source Code is in face_mask_detection.ipynb

#### How to Install:

Pre-Requisite: Python 3.7.x or greater

1. Clone the Repository Or Download Repo as Zip
2. Change Directory to face-mask-detection
3. Create an 'input' folder
4. now run maskcam.py file

