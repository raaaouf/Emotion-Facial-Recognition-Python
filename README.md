# Emotion---Facial-Recognition

## Dataset
  Download the dataset from  the da folder or the fer dataset from kaggle

## Model
  The model I use is a CNN of 4 layers which has the input from the HaarCascadeClassifier which sends the cropped image of face to CNN
  Either load the model I have trained whose architecture is in **model_anson.json** and **model_weights.h5**
  Or you can train your own model using the **Facial_Expression_Training.ipynb** file
  
## Template
  Design a html to display the annonated video at your localhost at port 5000
  
## Load model
  Use the **model.py**
  It loads the serialized json file back to a model which is used for prediction
  
## Display output
  Use the **camera.py**
  It has the required opencv operations for displaying the video with our required annonations
  In the video directory use your directory to locate your video to which you want output or you can use the "0" option to select your webcamera
  
## Final Flask integration
  Use the **main.py**
  In this script you will get the output from the camera.py file which in turn gets output form the model.py is used
  The flask framework is used to display the video at the localhost at port 5000
