# Speech-Recognition

Command Recognition App
Objective : To explore TinyML using Google's Tensorflow Lite and create a model that can be used to create an android application. 

Dataset used : Google's Minispeech Command Dataset 

Implementation : We first created a simple model for command recognition and then converted that model into a Tflite model.
                 We then created a basic android application to receive audio input in real-time and pass that audio to the lite model to recognize the command. 
                 The app then finally displays the output of the model, i.e. the predicted command and the corresponding percentage of it being the correctly identified command. 
