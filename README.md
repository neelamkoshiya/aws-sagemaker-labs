# aws-sagemaker-labs
AWS sagemaker examples
Prerequisites
AWS Account

Permissions: In order to complete this workshop you'll need an AWS Account, and an AWS IAM user in that account with at least full permissions to the following AWS services:

    AWS IAM
    Amazon S3
    Amazon SageMaker
   
Use Your Own Account: The code and instructions in this workshop assume only one student is using a given AWS account at a time. If you try sharing an account with another student, you'll run into naming conflicts for certain resources. You can work around these by appending a unique suffix to the resources that fail to create due to conflicts, but the instructions do not provide details on the changes required to make this work. Use a personal account or create a new AWS account for this workshop rather than using an organization’s account to ensure you have full access to the necessary services and to ensure you do not leave behind any resources from the workshop.

Costs: Some, but NOT all, of the resources you will launch as part of this workshop are eligible for the AWS free tier if your account is less than 12 months old. See the AWS Free Tier page for more details. An example of a resource that is not covered by the free tier is the Amazon SageMaker notebook instance type used in some workshops. To avoid charges for endpoints and other resources you might not need after you've finished a workshop, please refer to the Cleanup Guide.
AWS Region

Amazon SageMaker is not available in all AWS Regions at this time. Accordingly, we recommend running this workshop in one of the following supported AWS Regions: N. Virginia, Oregon, Ohio, or Ireland.

Once you've chosen a region, you should create all of the resources for this workshop there, including a new Amazon S3 bucket and a new SageMaker notebook instance. Make sure you select your region from the dropdown in the upper right corner of the AWS Console before getting started.

Region selection screenshot
