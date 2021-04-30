## Sentiment Analysis Web Application
---
This project was carried out as a requirement of Udacity's Deep Learning Nanodegree Program. The main idea of the project is to develop a Sentiment Analysis model using a Long Short-term Memory (LSTM) network and deploy it using AWS Sagemaker, Lambda and API Gatway.

The project explores Recursive Neural Networks (RNNs), APIs and deployent.

### Files in this Repository

SageMaker Project.ipynb: a Jupyter Notebook with all the code
report.html: an html version of the Jupyter Notebook
train.py: training file required by SageMaker training job
predict.py: prediction file to adapt Sagemaker's end-point to use pytorch model
index.html: Website that consumes the final end-point

### Used Libraries

- pytorch
- nltk
- BeautifulSoup
- numpy
- sagemaker
- scikit-learn