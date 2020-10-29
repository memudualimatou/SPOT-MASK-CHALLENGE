# SPOT-MASK-CHALLENGE

***A Face Mask Detection system built with OpenCV, Deep Learning and Computer Vision.***

## INSPIRATION

The most effective way of protecting each other during the COVID-19 pandemic is wearing a face mask, thos is where the motivation of creating a system built using deep learning model to identify a person wearing a mask or not, what can be used in crowdy place such as station, schools etc.

## TECHNOLOGY USED

* [OPENCV](https://opencv.org/about/)
* [TensorFlow](https://www.tensorflow.org/)
* [KERAS](https://keras.io/)
* [MobileNet](https://keras.io/api/applications/mobilenet/)
* [Caffe based face detector](https://caffe.berkeleyvision.org/)

## SYSTEM 

THE data used in this project is from a Zindi Africa, [The spot mask Challenge](https://zindi.africa/competitions/zindiweekendz-learning-spot-the-mask-challenge) , after participating in the competition I had the idea of using the data to built a face mask detector.

I built a deep learning model `Spotmask.ipynb `, transfer learning used pretrained MobileNet application and performed a data augmentation by scaling the images to obtain a very accurate model.
Saved the model and used it to build a system  `video.py ` to predict if a person is wearing a face mask or not .

## DATASET

As mentioned earlier, the dataset is from a Zindi Africa competition, download it here [CLICK HERE ](https://zindi.africa/competitions/zindiweekendz-learning-spot-the-mask-challenge/data)

This dataset consists of 3 elements:
 * An image zip file that contains the images 
      * MASK: 1308 images
      * NO-MASK: 509 images
 * A train labels file
 * Aample of the submission file

## RESULT
![mask detector](https://github.com/memudualimatou/SPOT-MASK-CHALLENGE/blob/master/ezgif.com-gif-maker.gif)
