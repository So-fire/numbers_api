# Number Classification API

## Overview
This is a simple Number Classification API built to classify numbers into categories: Odd or Even. The API is deployed as an AWS Lambda function, which can be invoked to determine whether a given number is odd or even.

## Features
- **Number Classification**: The API accepts a number and returns whether it is Odd or Even.
- **Serverless Architecture**: Deployed using AWS Lambda for efficient serverless operation.
- **API Gateway Integration**: Exposed through API Gateway for easy HTTP access.

## Getting Started

### Prerequisites
Ensure you have the following installed before proceeding:
- **AWS CLI**: For managing AWS resources.
- **Python 3.x**: The language used for the Lambda function.
- **AWS Lambda Console / AWS SAM**: For deploying the function.
- **API Gateway**: To expose the function via HTTP requests.

### Installation
- request
  pip install requests -t .

After the installation, file was zip and uploaded to lambda, where it was deployed and tested.

### API GATEWAY CREATION
API was created and integrated with Lambda function that was created and http.
