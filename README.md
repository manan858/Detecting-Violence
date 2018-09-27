# Detecting-Violence
Implementation of the model ( Violence Detection using CNN+ LSTM)

The proposed model has the following advantages:

1. The ability to use the pre-trained model on ImageNet dataset.
2. The ability to learn the local motion features by examined the concatenated two frames using CNN.
3. The ability to learn the global temporal features by LSTM cell.

Implementation is done with Keras and TensorFlow as a back-end. The model incorporates pre-trained convolution Neural Network (CNN) connected to Convolutional LSTM (ConvLSTM) layer. The model takes as an inputs the raw video, converts it into frames and output a binary classication of violence or non-violence label.


# Running configurations

Video Dataset Path:
hockey - /home/manan/ViolenceDetection/hockey

# Libraries Required:
 python 2.7
 
 numpy 1.14.0
 
 keras 2.2.0
 
 tensorflow 1.9.0
 
 Pillow 3.1.2
 
 opencv-python 3.4.1.15

# Running Operation:
Run  python run.py
