# Sentiment Analysis using Sagemaker with Tensorflow


This lab helps with sentiment analysis with tensorflow on AWS Sagemaker.

## Breif description about the lab: 
Sentiment Analysis with TensorFlow
A Convolutional Neural Net (CNN) is sometimes used in text classification tasks such as sentiment analysis. We'll use a CNN built with TensorFlow to perform sentiment analysis in Amazon SageMaker on the IMDB dataset, which consists of movie reviews labeled as having positive or negative sentiment. Three aspects of Amazon SageMaker will be demonstrated:

How to use Script Mode with a prebuilt TensorFlow container, along with a training script similar to one you would use outside SageMaker.
Local Mode training, which allows you to test your code on your notebook instance before creating a full scale training job.
Batch Transform for offline, asynchronous predictions on large batches of data.

## Prerequisites

Download this project, unzip it.

AWS Account

Permissions: In order to complete this workshop you'll need an AWS Account, and an AWS IAM user in that account with at least full permissions to the following AWS services:

    AWS IAM
    Amazon S3
    Amazon SageMaker
  
   
Use Your Own Account: The code and instructions in this workshop assume only one student is using a given AWS account at a time. If you try sharing an account with another student, you'll run into naming conflicts for certain resources. You can work around these by appending a unique suffix to the resources that fail to create due to conflicts, but the instructions do not provide details on the changes required to make this work. Use a personal account or create a new AWS account for this workshop rather than using an organization’s account to ensure you have full access to the necessary services and to ensure you do not leave behind any resources from the workshop.

Costs: Some, but NOT all, of the resources you will launch as part of this workshop are eligible for the AWS free tier if your account is less than 12 months old. See the AWS Free Tier page for more details. An example of a resource that is not covered by the free tier is the Amazon SageMaker notebook instance type used in some workshops. To avoid charges for endpoints and other resources you might not need after you've finished a workshop, please refer to the Cleanup Guide.
AWS Region

Amazon SageMaker is not available in all AWS Regions at this time. Accordingly, we recommend running this workshop in one of the following supported AWS Regions: N. Virginia, Oregon, Ohio, or Ireland.


## Steps:

Download this project, unzip it.
![Alt text](images/img0.png?raw=true "Download project zip")



1) Go to AWS Console and search for Sagemaker
![Alt text](images/img1.png?raw=true "AWS Console - Sagemaker")
2) Once in Sagemaker, create a notebook instance. Put in the name - "yourinitals"-Labs. 
    ![Alt text](images/img2.png?raw=true "Notebook")
    
    ![Alt text](images/img3.png?raw=true "Notebook")
3) Go to IAM and select create a new IAM role, ensure the role has access to S3 buckets (FullS3access)
![Alt text](images/img4.png?raw=true "Notebook")


![Alt text](images/img5.png?raw=true "Notebook")


![Alt text](images/img6.png?raw=true "Notebook")

It will take some time to create the notebook. Note the change in the status

![Alt text](images/img7.png?raw=true "Notebook")

4) Once the notebook is created and in "In Service" Status click open the jupyter which will open the jupyter notebook

![Alt text](images/img8.png?raw=true "Notebook")

Click this button

![Alt text](images/img9.png?raw=true "Notebook")

5) Import the notebook by clicking upload and browse from your downloaded files ( 	sentiment-analysis.ipynb)

![Alt text](images/img10.png?raw=true "Notebook")

![Alt text](images/img11.png?raw=true "Notebook")

6) Once the file is loaded, open the notebook
![Alt text](images/img12.png?raw=true "Notebook")

7) Clear the cell output. Then Click on the block and hit the run button. You can read the details of the steps and also output after every execution.
![Alt text](images/img13.png?raw=true "Notebook")




