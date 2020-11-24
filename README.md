# Machine Learning, Deployment Case Study with AWS SageMaker

This repository contains code and associated files for deploying a ML model using AWS SageMaker. This repository consists of a tutorial notebook for a case study on payment fraud detection that will be used to illustrate parts of the ML workflow and give you practice deploying ML algorithms.

### Tutorial

* [Payment Fraud Detection](https://github.com/udacity/ML_SageMaker_Studies/tree/master/Payment_Fraud_Detection): Learn how to build and deploy a supervised, LinearLearner model in SageMaker. You'll tune a model and handle a case of class imbalance to train a model to detect cases of credit card fraud.

---

## Setup Instructions

The notebooks provided in this repository are intended to be executed using Amazon's SageMaker platform. The following is a brief set of instructions on setting up a managed notebook instance using SageMaker, from which the notebooks can be completed and run.

### Log in to the AWS console and create a notebook instance

Log in to the [AWS console](https://console.aws.amazon.com) and go to the SageMaker dashboard. Click on 'Create notebook instance'.
* The notebook name can be anything and using ml.t2.medium is a good idea as it is covered under the free tier. 
* For the role, creating a new role works fine. Using the default options is also okay. 
* It's important to note that you need the notebook instance to have access to S3 resources, which it does by default. In particular, any S3 bucket or object, with “sagemaker" in the name, is available to the notebook.
* Use the option to **git clone** the project repository into the notebook instance by pasting `https://github.com/udacity/ML_SageMaker_Studies.git`

### Open and run the notebook

Now that the repository has been cloned into the notebook instance you may navigate to the notebook to complete or execute and work with them. Additional instructions are contained in the notebook.
