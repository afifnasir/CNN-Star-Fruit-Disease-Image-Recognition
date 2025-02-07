Starfruit Condition Prediction using CNN
Overview
This project focuses on predicting the condition of starfruits (healthy or unhealthy) using a Convolutional Neural Network (CNN). The trained model evaluates images of starfruits and classifies them based on their health condition. The repository contains the dataset, preprocessing scripts, and the model used for prediction.

Features
Binary Classification: Classifies starfruits into two categories:
Healthy Fruit
Unhealthy Fruit
Image Processing: Preprocesses input images for compatibility with the CNN model.
Model: A pre-trained or custom-built CNN model fine-tuned for this task.
Visualization: Displays input images and their corresponding predictions.
Dataset
The dataset contains images of starfruits in two conditions:

Healthy: Images of starfruits in good condition.
Unhealthy: Images of starfruits with visible defects.
Model
The CNN model was trained using Keras and TensorFlow. It accepts preprocessed images as input and outputs a prediction score, which determines the classification label.

How It Works
Preprocessing: Images are resized and normalized.
Prediction: The model predicts the condition of the fruit based on the input image.
Output: The result is displayed along with the input image.
