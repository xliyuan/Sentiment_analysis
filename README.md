# SageMaker Deployment Project

The notebook and Python files provided here, once completed, result in a simple web app which interacts with a deployed recurrent neural network performing sentiment analysis on movie reviews. This project assumes some familiarity with SageMaker.

# Any cost?
The deployment project which you will be working on is intended to be done using Amazon's SageMaker platform. In particular, it is assumed that you have a working notebook instance in which you can clone the deployment repository.

When starting your AWS you will get some free resources. For Sagemaker it is free to use some instances for the first two months. Please check carefully on Free Tier limits https://aws.amazon.com/free/?all-free-tier.sort-by=item.additionalFields.SortRank&all-free-tier.sort-order=asc and pricing https://aws.amazon.com/sagemaker/pricing/

Attention, in order to avoid incurring unnecesecary cost, please make sure to clean up the Sagemaker resources, such as terminate the end points, delete the instances and trainging jobs, as well as delete the buckets and IAM roles. Below I have provided you with a link to follow https://docs.aws.amazon.com/sagemaker/latest/dg/ex1-cleanup.html 
