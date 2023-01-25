# Emotion-AI
Face Emotion recognition using 2 models both classification and regression, CNN and Tensorflow 2.0 #Modern Ai Project

Emotion AI allows computers to understand human non-verbal cues such as body language and facial expressiona

An input image will fed to 2 AI models.

--> One predicts the key facial points in human faces
--> The second one is a classification model which says if the person's face is happy or not

# Part 1: Key Facial Points Discussion

A deep learning model will be created based on CNN to predict facial key points

Dataset contains x and y coordinates of 15 facial key points. Input Images are 96x96 pixels and only grayscale

0 - black image
255 - white image
1 to 254 - gray image

## Step 1: Upload the dataset and import the required libraries
Required Libraries: Pandas, Numpy, OS, PIL, Seaborn, Tensorflow, CV2

## Step 2: Load the data into a pandas dataframe

## Step 3: Obtain relevant information about the dataframe

## Step 4: Convert the Image shape to 96x96 using lambda function
Since the shape is 1 D array of 2140 rows
