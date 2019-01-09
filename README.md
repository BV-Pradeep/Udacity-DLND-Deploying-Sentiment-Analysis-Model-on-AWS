# Udacity-Deep-Learning-Nanodegree-Project5-Deploying-Sentiment-Analysis-Model
This my submission for Udacity Deep Learning Nanodegree Project for Deploying a Sentiment Analysis Model on AWS

[//]: # (Image Reference)

[image1]: ./Submission_Negative_1.jpg "Negative Review"
[image2]: ./Submission_Positive_1.jpg "Positive Review"
# Deploying a Sentiment Analysis Model

## Project Overview
In this project, I used SageMaker to construct a complete project from end to end. The goal of this project is to have a simple web page which a user can use to enter a movie review. The web page will then send the review off to my deployed model which will predict the sentiment of the entered review.

![Negative Review][image1]


![Positive Review][image2]
## Project Instruction

### Instruction

1. Clone the repository and navigate to the downloaded folder.
	```
		git clone https://github.com/PradeepVenna292/Udacity-Deep-Learning-Nanodegree-Project5-Deploying-Sentiment-Analysis-Model
	```
2. Open the `SageMaker Project.ipynb` file. Of course, you can find HTML version of the file.
	```
		jupyter notebook SageMaker Proejct.ipynb
	```
3. Read and follow the instructions! You can find and download the dataset for this project in the notebook.

## Project Information

### Contents

- General Outline
- Step 1: Downloading the data
- Step 2: Preparing and Processing the data
- Step 3: Upload the data to S3
- Step 4: Build and Train the PyTorch Model
- Step 5: Testing the Model
- Step 6: Deploying the model for testing
- Step 7: Use the model for testing
- Step 6 (again): Deploy the model for the web app
- Step 7 (again): Use the model for the web app

### Libraries

The list below represents main libraries and its objects
for the project.
- [Amazon SageMaker](https://ap-northeast-2.console.aws.amazon.com/sagemaker/home?region=ap-northeast-2#/landing) (Build, train, and deploy a model)
- [PyTorch](https://pytorch.org) (LSTM classifier)

### Delete the Endpoint
Remember to always __SHUT DOWN YOUR ENDPOINT__ if you are no longer using it. You are charged for the length of time that the endpoint is running so if you forget and leave it on you could end up with an unexpectedly large bill.

### Request Limit increase for Sagemake Training and Sagemaker Notebook Instances 
Submit a request to AWS to increase both limits of Sagemaker Notebook and Sagemaker Training instances of ml.p2.xlarge to 1
For faster execution of the project.
