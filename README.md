# Sign-Language-Detection

Real-Time Sign Language Detection Project using a WebCam.
Currently working on this project and after completed then move it to mobile devices.

Download link for dataset: https://www.kaggle.com/grassknoted/asl-alphabet/kernels

Here I using the pre-trained model i.e Mobilenet_v2

Due to Hardware restriction, I train Model on Kaggle playground.
Validation Accuracy = 0.9947917 and Validation Loss = 0.03621217922773212

Main File :- "Sign Language Detection (kaggle).ipynb" and "Real Done.py"

![](validation%20score.JPG)

Now, the Project is on the Real-Time i.e When you capture the image from the web then the model takes that image and predicts the Alphabet.
See the code "Real-time.py" or "Real Done.py" for using the model in Real-time Basis.

NOTE:- Here's an important note that when you do real-time predictions (by using the Real-time.py or Real Done.py) than you have to keep in mind that the images which you are capturing should be neat having clean background and the intensity of the light should be moderate NO high and NO low intensity.

Real Done.py file is the file for computer vision. Below are some screenshots of that file in running using the trained model on American Sign Language Detection datasets.

![](Capture2.jpg)

![](Capture1.jpg)

Now, Finally my project is deployed on mobile device
![](H_pred.png)
![](W_pred.png)
