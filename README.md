# Vigilant-Drive-Monitoring-System-Using-Transfer-Learning
Driver drowsiness detection is crucial for road safety. This study leverages transfer learning with pre-trained CNNs, fine-tuned to detect fatigue via facial features, eye movements, and head posture, improving accuracy and generalization in real-time. The approach offers a reliable, scalable solution to reduce accidents and save lives.

## Introduction
Driver drowsiness is one of the leading causes of road accidents globally. To mitigate this issue, we have developed an advanced **drowsiness detection system** that leverages the power of **transfer learning** combined with **Convolutional Neural Networks (CNNs)**. This system is designed to monitor real-time video input, track key facial and physiological features, and predict driver fatigue with high accuracy.

## Key Features:
- **Transfer Learning**: Fine-tuning a pre-trained CNN model for drowsiness detection.
- **Real-Time Monitoring**: Continuous monitoring of facial features, eye blinks, and head movements.
- **High Accuracy & Generalization**: Improved detection through a robust model architecture, trained on specialized datasets.
- **Scalability**: The model can be deployed in various real-world environments and integrated into modern intelligent transportation systems.

## Process:
![image](https://github.com/user-attachments/assets/72891164-9b9c-43de-947d-8e97d91af810)

## Model Architecture:
![image](https://github.com/user-attachments/assets/002f874b-858b-4f33-a8b5-ecc507e058a0)




## How It Works:
1. **Pre-Trained CNN Model**: We start with a CNN pre-trained on a large image dataset like **ImageNet**, which knows how to identify general image patterns.
2. **Fine-Tuning with Drowsiness Data**: The pre-trained model is then fine-tuned using a custom dataset focused on driver drowsiness indicators such as **eye closure rate, yawning frequency,** and **head tilt**.
3. **Prediction**: Based on real-time inputs, the system predicts whether the driver is alert, drowsy, or needs immediate intervention.

![image](https://github.com/user-attachments/assets/b347c1e8-55f4-4bb5-9e09-a11d6840ebb4)


## Dataset:
The model is fine-tuned using a custom dataset specifically tailored for drowsiness detection. This dataset includes labeled images and videos capturing **eye closure patterns, head posture,** and other physiological indicators associated with fatigue.

DataSet For Closed Eyes:
![image](https://github.com/user-attachments/assets/c82b3baa-1fb3-47ff-9ee2-9f8ba154d811)

DataSet For Open Eyes:
![image](https://github.com/user-attachments/assets/f6acd339-4076-42a5-a02b-4d0ca258334c)



## Technologies Used:
- **Python**
- **TensorFlow/Keras** for deep learning
- **OpenCV** for real-time video analysis
- **Transfer Learning** with CNNs

## Getting Started:
To run this project on your local machine:


### Requirements:
- **Python 3.x**
- **TensorFlow**
- **OpenCV**
- Pre-trained CNN model (e.g., **ResNet50, MobileNetV2**)



