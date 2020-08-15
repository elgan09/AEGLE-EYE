# AEGLE-EYE
github for training Deep Learning Model for eye disease classification
Tools: Tensorflow 2, keras, OpenCV, numpy, pandas, sklearn, seaborn,  matplotlib Flask, Ngrok


Dataset:
from Multiple Sources: 
- Eye Disease from kaggle: prateek0x/eye-disorder-dataset 
- Normal Eye from Kaggle: kayvanshah/eye-dataset

LINK: 
https://drive.google.com/drive/folders/1-Huc9X_WvlLI8q5IS_tO8tYguN-KouYa?usp=sharing
OR (IN .H5 format): https://drive.google.com/file/d/1-r6IRlBZiWeTe7aLpd0H9TFI4TXkDq1h/view?usp=sharing

Model: 
model is loaded by this line:
new_model = tf.keras.models.load_model('/content/drive/My Drive/Colab Notebooks/Eyes_GH/first_Mod6.h5')
Network:  2 Convolutional layers, Max Pooling, DropOut, 2 Convolutional layers, Max Pooling, DropOut, Flatten , Dense, DropOut, Dense
Model: "sequential"
Total params: 11,206,436
Trainable params: 11,206,436

Google Colab for API testing:
https://colab.research.google.com/drive/1KPBl-_MhPyeHrn71KV1fPqNqgI1CxTdK?usp=sharing

Google Colab for face detection and eye disease classification:
https://colab.research.google.com/drive/1GnVru_iNhwya0_QfJyD0WIC6T4r4bsXp?usp=sharing
