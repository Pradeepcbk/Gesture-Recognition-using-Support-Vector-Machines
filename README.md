# Gesture-Recognition-using-Support-Vector-Machines
A project to implement a gesture recognition system using Support Vector Machines(SVM) from inertial sensors(3-d accelerometer)

### This project implements the paper:
https://link.springer.com/chapter/10.1007/978-3-642-02830-4_4

### The supervised learning algorithm of support vector machines is used for this purpose

## Working of the program:
1. The recorded gesture is to be tabulated in an excel sheet of the form "ACC.csv"
2. The file Feature_Extraction.py extracts the relevant data and forms a feature vector
3. The file Training&Learning.py uses the file in step 2 to train the SVM from the training data and predict the new incoming data.

Note: i. Currently only a binary classification problem is solved to recognise 2 gestures. However, it can be easily extended to a multi class classification by using ove-vs-all algorithm.
ii. The presentation of this project is in this link: https://www.slideshare.net/PradeepSiddagangaiah/gesture-recognition-usinginertialsensors
