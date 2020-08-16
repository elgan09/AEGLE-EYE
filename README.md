# AEGLE-EYE
github for training Deep Learning Model for eye disease classification
Tools: Tensorflow 2, keras, OpenCV, numpy, pandas, sklearn, seaborn,  matplotlib Flask, Ngrok


## Dataset:
from Multiple Sources: 
- Eye Disease from kaggle: prateek0x/eye-disorder-dataset 
- Normal Eye from Kaggle: kayvanshah/eye-dataset


## LINK To Download Trained Model during hackathons: 
https://drive.google.com/drive/folders/1-Huc9X_WvlLI8q5IS_tO8tYguN-KouYa?usp=sharing
OR (IN .H5 format): https://drive.google.com/file/d/1-r6IRlBZiWeTe7aLpd0H9TFI4TXkDq1h/view?usp=sharing


## Model: 

model is loaded by this line:

  new_model = tf.keras.models.load_model('/content/drive/My Drive/Colab Notebooks/Eyes_GH/first_Mod6.h5')

Network:  2 Convolutional layers, Max Pooling, DropOut, 2 Convolutional layers, Max Pooling, DropOut, Flatten , Dense, DropOut, Dense

Model: "sequential"

Total params: 11,206,436

Trainable params: 11,206,436

Input is face images, the detected eye data is classified by our machine learning model into normal eyes, bulked eyes, crossed eyes, and cataract eyes. '

The accuracy reached by our model is 98.69%


## Here is the link for accessing colab: Google Colab for face detection and eye disease classification:
https://colab.research.google.com/drive/1GnVru_iNhwya0_QfJyD0WIC6T4r4bsXp?usp=sharing

### First we download the datasets from multi-resources and perform pre-processing to prepare the data to be given to the network. The dataset also being suffled and divided into training data, validation data, and testing data. 

### Then we designed the network using Sequential()

### We performed the training for 50 epochs. We see the dataset is not large about 219 eyes dataset consists of diseased and normal eyes.

### Evaluate, perfom confusion mactrixes, and save model

## Google Colab for API testing:
https://colab.research.google.com/drive/1KPBl-_MhPyeHrn71KV1fPqNqgI1CxTdK?usp=sharing

### Here in this Notebook, we already have the trained model from the provious Google colab's link. We load the model and prepare the input image to be tested on the Flask API. We also use Ngrok.io so we can access the model from outside of Google Colab.

### We also can checked the trained by giving an input image to eyedisease_detection(img) or predict(img). The eyedisease_detection(img) is equipped with face detection feature.
