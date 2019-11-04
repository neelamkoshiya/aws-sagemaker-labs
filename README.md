# aws-sagemaker-labs
AWS sagemaker examples
Prerequisites

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


Steps:
Download this project, unzip it.
![Alt text](images/img0.png?raw=true "Download project zip")



1) Go to AWS Console and search for Sagemaker
![Alt text](images/img1.png?raw=true "AWS Console - Sagemaker")
2) Once in Sagemaker, create a notebook instance. Put in the name - <<yourinitals>>-Labs. 
    ![Alt text](images/img2.png?raw=true "Notebook")
    
    ![Alt text](images/img3.png?raw=true "Notebook")
3) Go to IAM and open the IAM role, ensure the role(which you copied in previous step) has access to S3 buckets (FullS3access)
4) Once the notebook is created click open the jupyternotebook
5) Import the notebook by clicking upload and browse from your downloaded files ( 	sentiment-analysis.ipynb)
6) Once the file is loaded, open the notebook
7) Click on the block and hit the run button
8) You can read the details of the steps and also output after every execution.



