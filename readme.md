# Violence detection and Alert System (FINAL YEAR PROJECT)
This project presents a deep learning-based violence detection system using MobileNetV2 and LSTM to analyze video data for real-time threat identification. With techniques like data augmentation and hyperparameter tuning, the model achieves improved accuracy. It is integrated with a Telegram bot to send instant alerts with images and timestamps, supporting smart surveillance applications.



## Architecture Diagram
![](<Alert System/Model diagram.png>)


## Model Poster 
![](<Alert System/model poster.png>)



# Repo Modules

## Module 1 (Violence Detection)
A real-time violence detector using MobileNetV2 and LSTM a hybrid model leveraging transfer learning ,where MobileNetV2 used as a feature extractor and LSTM used for modeling and predicting spatio-temporal data giving the output in the form of images with the result printed writen on each image using OpenCV, implemented using python.Also  we are using data augmentation to artificially increase the size and diversity of training data .

## Module 2 (Alert System)
Creating a telegram bot and a telegram group, adding the bot to the group that send alert messages whenever violence is detected in any frame, send the 30th violence=true frame to the telegram group using the bot, including a message which contains details like Location, Time and Date etc

## Module 3 (Results)
This module contain results of our model. Screenshots of general metrics such as Training and Validation Accuracy,Training and Validation Losses,
Confusion MAtrix, AUC-ROC Curve, Sample size, best epoch,MCC Score etc.
## Module 4 (Documents)
This module cover basic information  of our model such as model diagram,
Research paper etc 