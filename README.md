# Emotion_Detection_CNN_
Realization of an application allowing to determine a facial expression of a person or several with the help of CNN.
 + Read and balance the dataset with their labels. 
 + Divide the dataset into a training phase and a test phase. 
 + Automatically extract features via CNN and do the training. 
 + Evaluate the model to know the accuracy. 
 + Predict which class an image query belongs to
Packages need to be installed
+ pip install numpy
+ pip install opencv-python
+ pip install keras
+ pip3 install --upgrade tensorflow
+ pip install pillow
download FER2013 dataset
from below link and put in data folder under your project directory
https://www.kaggle.com/msambare/fer2013
Train Emotion detector
with all face expression images in the FER2013 Dataset
command --> python TranEmotionDetector.py
It will take several hours depends on your processor. (On i7 processor with 16 GB RAM it took me around 4 hours) after Training , you will find the trained model structure and weights are stored in your project directory. emotion_model.json emotion_model.h5

copy these two files create model folder in your project directory and paste it.

run your emotion detection test file
python TestEmotionDetector.py

