# Deploying a Sentiment Analysis Model

## Project Overview
In this project, I have used SageMaker to complete project from end to end. The goal is to build a simple web app in which users can submit a movie review and the prediction model (RNN model) will make a predicton whether the review is positive or negative. 

## Project instruction 
This project requires GPU instances for training models. Recommend using AWS instead of running on local machine. 

1. Clone the repository 

```git clone https://github.com/leedat152/sentiment_analysis.git```

2. Open the SageMaker Project.ipynb file. 

```jupyter notebook SageMake Project.ipynb```

3. Read and follow the instructions! This file will guide you to download the dataset for this project 

## Project Information

### Contents 
- Step 1: Downloading the data
- Step 2: Preparing and Processing the data
- Step 3: Upload the data to S3
- Step 4: Build and Train the Pytorch Model 
- Step 5: Tesitng the model 
- Step 6: Deploy the model for web app
- Step 7: Use the model for web app 

### Libraries
- Amazon SageMaker (Build, train, and deploy a model)
- Pytorch (LSTM classifier)

## Delete the endpoint
Remember to always **SHUT DOWN YOUR ENDPOINT** if you are no longer using it. You are charger for the length of tume that the endpoint in running so if you forget and leave it running, you could end up an unexpectedly large bill :fire:

```predictor.delete_endpoint()```
