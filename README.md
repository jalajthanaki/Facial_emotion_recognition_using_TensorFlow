# Emotion recognition CNN based approach using TensorFlow


This repository is the out project about Face emotion recognition using convolutional neural network. 

![video_screenshot_16 02 2018](https://user-images.githubusercontent.com/12840374/36300907-0f8bfe86-1329-11e8-88c7-402236458387.png)

## Dependencies

- [NumPy](http://docs.scipy.org/doc/numpy-1.10.1/user/install.html)
- [Tensorflow](https://www.tensorflow.org/versions/r0.8/get_started/os_setup.html)
- [TFLearn](https://github.com/tflearn/tflearn#installation)
- [OpenCV](https://opencv-python-tutroals.readthedocs.io/en/latest/)

## Dataset

We use the [FER-2013 Faces Database](http://www.socsci.ru.nl:8180/RaFD2/RaFD?p=main), a set of 28,709 pictures of people displaying 7 emotional expressions (angry, disgusted, fearful, happy, sad, surprised and neutral).

You have to request for access to the dataset or you can get it on [Kraggle](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data).

## Train 
```bash
$ python emotion_recognition.py train
```

## Test

```bash
$ python emotion_recognition.py poc
```

## Paper

[Link](https://github.com/isseu/emotion-recognition-neural-networks/blob/master/paper/Report_NN.pdf)

## Credit

This code credit goes to [Enrique Correa](https://github.com/isseu). I've merely created a wrapper to get people started.