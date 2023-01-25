# Sentiment analysis using face detection.

The goal of this project is to apply python's tensorflow library to build a system capable of classifying facial expression into 1 of 7 categories: Sad, Happy, Neutral, Angry, Disgust, Surprise and Fear. We will compare our CNN with an in-built python library called FER that has the same objective. Our objective here is to improve FER's precision when classifying expresions, or at least obtain a benchmark to compare the accuracy obtained by our model. In order to do so, we will construct a Convolutional Neural Network and train it using the images contained in the fer2013 dataset, the same dataset used to create the FER library mentioned before. We recommed to connect an external GPU to speed up this process, since its nature can make it quite lenghty and most computers won't be capable of handling it. Finally, we decided to generalize our CNN to work with all kind of pictures, so users can upload their own colored picture and get an estimation of their state. This represents an advantage with respect to FER, which works only with black and white pictures. 


# Link to download the dataset used:
https://www.kaggle.com/competitions/challenges-in-representation-learning-facial-expression-recognition-challenge/data?select=fer2013.tar.gz
