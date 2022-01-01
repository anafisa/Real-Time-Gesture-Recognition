# Real-Time-Gesture-Recognition


Image Recognition is the task of identifying objects of interest within an image and recognizing which category they belong to. The common goal of image recognition is the classification of detected objects into different categories. 


This repository contains project I've done during the course work. The primary objective of this project is to build a Real-Time Gesture Recognition (Classification) Model. 
This model can be proposed as a baseline model for sign interpreter, which automatically converts sign language into written output to make communication for dumb people easy.


Both the training and testing [data](https://www.kaggle.com/datamunge/sign-language-mnist) are stored as 785 columns where the first column 'label' contains numbers 0 - 25 representing letters of the alphabet and the remaining 784 columns contain values (0 - 255) which correspond to pixel intensities for the 28x28 pixel images of each sign language hand gesture.


<img width="477" alt="Снимок экрана 2022-01-01 в 22 40 06" src="https://user-images.githubusercontent.com/30799388/147858812-24eb9df0-35fa-44f0-a838-447f8af4dae2.png">


<img width="474" alt="Снимок экрана 2022-01-01 в 22 40 16" src="https://user-images.githubusercontent.com/30799388/147858819-a71e3694-8d63-46b5-834b-c1afc472395e.png">


The final [CNN model](https://github.com/anafisa/Sign-Language-Classification/blob/main/Models/sign-language-cnn.ipynb) achieved 100% accuracy:

<img width="852" alt="Снимок экрана 2022-01-01 в 22 59 06" src="https://user-images.githubusercontent.com/30799388/147859126-34ad4777-81f8-435d-8072-6fa11bf9d166.png">




![demog](https://user-images.githubusercontent.com/30799388/146651464-fa939588-d9d3-402f-80df-daf430fe92c5.gif)

![short2](https://user-images.githubusercontent.com/30799388/146783843-aa67e5f0-e149-463c-b76b-33091e7cdca7.gif)

![short3](https://user-images.githubusercontent.com/30799388/146785561-7e557b46-e4cb-471f-af42-7fc842fff284.gif)
