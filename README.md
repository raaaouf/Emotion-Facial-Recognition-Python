# web based Emotion Facial Recognition using python 
![cover](https://github.com/raaaouf/Emotion-Facial-Recognition-Python/blob/main/download.png)

<p align="center">
  <img alt="License" src="https://img.shields.io/badge/license-MIT-%237159c1">
  

  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/raaaouf/Emotion-Facial-Recognition-Python?color=%237159c1">
  

  <img alt="Made by raaaouf " src="https://img.shields.io/badge/made%20by-raaaouf-%237159c1">  
 

  <img alt="Top Language" src="https://img.shields.io/github/languages/top/raaaouf/Emotion-Facial-Recognition-Python?color=%237159c1">
</p>

this is a real time deep learning project 🔥 for Emotion Facial Recognition 😁 using python ,openCV and flask backend 📸

## Dataset
  Download the dataset from kaggle [here](https://www.kaggle.com/c/emotion-detection-from-facial-expressions/data)

## Model
  The model I use is a CNN of 4 layers which has the input from the HaarCascadeClassifier which sends the cropped image of face to CNN
  Either load the model I have trained whose architecture is in **model_anson.json** and **model_weights.h5**
  Or you can train your own model using the **Facial_Expression_Training.ipynb** file
  
## Template💙
  Use the html tamplate file to display the annonated video at your localhost at port 5000
  
## Load model
  Use the **model.py**
  It loads the serialized json file back to a model which is used for prediction
  
## Display output
  Use the **camera.py**
  It has the required openCV operations for displaying the video with our required annonations
  In the video directory use your directory to locate your video to which you want output or you can use the "0" option to select your webcamera
  
## Final Flask integration
  Use the **main.py**
  In this script you will get the output from the camera.py file which in turn gets output form the model.py
  
  flask framework is used to display the video at the localhost at port 5000


## Contributing 🙌
### Step 1
- **give me a star! 🌟**🌟 

### Step 2

- **Option 1**
    - 🍴 Fork this repo!

- **Option 2**
    - 👯 Clone this repo 
### Step 3
- **HACK AWAY!** 🔨🔨🔨


## License 📝

- [MIT](http://opensource.org/licenses/mit-license.php) License.

<h4 align="center">
<a href="http://linkedin.com/in/raoufzoghbi">Connect me in LinkedIn </a> | <a href="https://medium.com/@raaaaouf">See my Medium </a>👀 | <a href=" ">Click here to go to my CV</a>
</h4>
