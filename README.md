# A Gesture-Based Tool For Sterile Browsing Of Radiology Images

# Demo Link

<a href="https://youtu.be/K9eYGN4LOA0">Click Here for Demo Video</a>

# Team Members:

    1. Dinesh Kumar S[TL] -111919106008

    2. Balaji N[TM1] -111919106002

    3. Syed Farook M[TM2] - 111919106061

    4. Udit Kumar B[TM3] - 111919106063

    5. Eswar R[TM4] - 111919106303

# INTRODUCTION:

        ⦿ Humans are able to recognize body and sign language easily. This is possible due to the combination of vision
    and synaptic interactions that wereformed along brain development . In order to replicate this skill in computers,
    some problems need to be solved: how to separate objects of interest in images and which image capture technology and
    classification technique are more appropriate, among others.

        ⦿ In this project Gesture based Desktop automation ,First the model is trained pre trained on the images of different
    hand gestures, such as a showing numbers with fingers as 1,2,3,4 . This model uses the integrated webcam to capture the video
    frame. The image of the gesture captured in the video frame is compared with the Pre-trained model and the gesture is identified.
    If the gesture predictes is 1 then images is blurred;2, image is resized;3,image is rotatedm etc.

# PROJECT \ OBJECTIVE:

**By the end of this project you will**

    ➼ Know fundamental concepts and techniques of Convolutional Neural Network.

    ➼ Gain a broad understanding of image data.

    ➼ Know how to pre-process/clean the data using different data preprocessing techniques.

    ➼ Know how to build a web application using Flask framework.

# PROBLEM \ STATEMENT:

       ⦿ In this project we have used Convolutional Neural Network to frst train the model on the images of
      different hand gestures, like showing numbers with fngers as 0,1,2,3,4,5. Then we made a web portal
      using Flask where user can input any image on which he wants to perform the operations. After
      uploading the image, our portal uses the integrated webcam to capture the video frame using
      OpenCV. The gesture captured in the video frame is compared with the Pre-trained model and the
      gesture is identifed. If the prediction is

      0 - then images is converted into rectangle,
      1 - image is blurred,
      2 - image is rotated by -45॰,
      3 - image is resized in (400,400) ,
      4 - image is Resized in (200,200)  ,
      5 -image is converted into grayscale,

      but in real time we use of doctor-computer interaction devices in
      the operation room (OR) requires new modalities that support medical imaging manipulation while
      allowing doctors' hands to remain sterile, supporting their focus of attention, and providing fast
      response times.

# PROJECT \ FLOW:

    ⦿ User interacts with the UI (User Interface) to upload the image as input

    ⦿ Depending on the different gesture inputs different operations are applied to the input image.

    ⦿ Once model analyses the gesture, the prediction with operation applied on image is showcased on the UI.

**To accomplish this, we have to complete all the activities and tasks listed below**

    ➼ Data Collection.

        ⦿ Collect the dataset or Create the dataset

    ➼ Data Preprocessing.

        ⦿ Import the ImageDataGenerator library
        ⦿ Configure ImageDataGenerator class
        ⦿ Apply ImageDataGenerator functionality to Trainset and Testset

    ➼ Model Building

        ⦿ Import the model building Libraries
        ⦿ Initializing the model
        ⦿ Adding Input Layer
        ⦿ Adding Hidden Layer
        ⦿ Adding Output Layer
        ⦿ Configure the Learning Process
        ⦿ Training and testing the model
        ⦿ Save the Model

    ➼ Application Building

        ⦿ Create an HTML file
        ⦿ Build Python Code

# PROJECT \ STRUCTURE:

**Create a Project folder which contains files as shown below**

![image](https://user-images.githubusercontent.com/70817219/194914420-9ef53158-9413-447b-a7f3-846d5ed567cb.png)

    ⦿ Dataset folder contains the training and testing images for training our model.
    ⦿ We are building a Flask Application which needs  HTML pages stored in the templates
       folder and a python script app.py for server side scripting
    ⦿ we need the model which is saved and the saved model in this content is gesture.h5
    ⦿ The static folder will contain js and css files.
    ⦿ Whenever we upload a image to predict, that images is saved in uploads folder.

# TECHNICAL \ ARCHITECTURE:

![image](https://user-images.githubusercontent.com/70817219/194914841-4fc230f1-53f9-4b5a-8d9a-e902d9fc3581.png)

### IBM Project | Dept of Electronics & Communication Engineering | S A Engineering College
