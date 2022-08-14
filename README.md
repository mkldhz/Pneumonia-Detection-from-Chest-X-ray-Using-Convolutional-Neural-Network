# Pneumonia Detection from Chest X-ray Using Convolutional Neural Network
[Pneumonia](https://www.who.int/news-room/fact-sheets/detail/pneumonia) is a form of acute respiratory infection that affects the lungs. The lungs are made up of small sacs called alveoli, which fill with air when a healthy person breathes. When an individual has pneumonia, the alveoli are filled with pus and fluid, which makes breathing painful and limits oxygen intake.
<p align="center">
  <img src="https://www.nhlbi.nih.gov/sites/default/files/inline-images/pneumonia.png?raw=true"/>
</p>

## Goal
The aim was to take the [dataset](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia) which contains 5,863 X-Ray images, divided into normal and pneumonia, and to construct a convolutional neural network that is able to classify whether the given x-ray image can be diagonsed with pneumonia or not.

## CNN
The given netowrk utlizies [transfer learning](https://towardsdatascience.com/a-comprehensive-hands-on-guide-to-transfer-learning-with-real-world-applications-in-deep-learning-212bf3b2f27a), the network architecture is based on VGG16. The network was able to reach an accuray of 94% on the data test set.

## Metrics
The following metrics are of the network's performance over the test set:
* Overall Accuray: 94%
* Overall Recall: 96.67%
* Overall Precision: 94.01%
* AUC Score: 93%
<p align="center">
  <img src="https://github.com/mkldhz/Pneumonia-Detection-from-Chest-X-ray-Using-Convolutional-Neural-Network/blob/main/Screenshots/conf_matrix.jpg?raw=true"/>
</p>

## Predictions
Below is 16 images pulled randomly from the data test set, each image is labeled with the its true finding as well as the model prediction:
<p align="center">
  <img src="https://github.com/mkldhz/Pneumonia-Detection-from-Chest-X-ray-Using-Convolutional-Neural-Network/blob/main/Screenshots/predictions.jpg?raw=true"/>
</p>
