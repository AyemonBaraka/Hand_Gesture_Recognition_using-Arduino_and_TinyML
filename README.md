### Hand_Gesture_Recognition_using-Arduino_and_TinyML


In this project, I developed a system to recognize hand gestures using the Arduino Nano 33 BLE Sense board and its built-in IMU sensors (accelerometer and gyroscope). 

The gestures I focused on include punch, flex, and wave. I captured IMU data for each gesture and used this data to train a machine learning model with TensorFlow Lite.


After collecting the data for each gesture, I trained the model using Google Colab. Once the training was complete, I deployed the model back onto the Arduino board, enabling real-time gesture classification based on sensor inputs. 

The model could successfully classify the gestures with high confidence.

###Video Demo:

https://www.youtube.com/shorts/2aC55__KqOk
