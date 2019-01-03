# OpenCV_FaceDetection
Static Face Detection using OpenCV

# Prerequisites

* Python 3.x
* OpenCV 
* Numpy


# Installing

* Create 2 empty Folders named "dataset"  and "trainer "in the same directory where the python scripts are.

OR 

* Clone the repo and delete the files in trainer and dataset folder.

# Running the tests

First run the 01_face_dataset.py which will ask you to enter a unique id to create face samples with your face.
(I added Elon Musk's picture with Id - 1 and this Id will refered in 03_face_recognition.py)
![Screenshot 1](https://raw.githubusercontent.com/harshpalan/OpenCV_FaceDetection/master/Screenshots/ss1.png)
<br>
<br>

Then run 02_face_training.py (Before that check  the images in dataset folder)
![Screenshot 2](https://raw.githubusercontent.com/harshpalan/OpenCV_FaceDetection/master/Screenshots/ss2.png)

<br>
<br>
After this a trainer.yml will be created in the trainer folder.
Now Finally run 03_face_recognition.py

![Screenshot 3](https://raw.githubusercontent.com/harshpalan/OpenCV_FaceDetection/master/Screenshots/ss3.png)

<br>
<br>
The accuracy was less maybe due to using a image from mobile. It gives approx ~60% accuracy sometimes.😜🙈
