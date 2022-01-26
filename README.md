# aws-rekognition-facecompare
This repository compare a selfie with images from identity documents and response if the selfie match.

This code was made in a notebook under SageMaker.

### Set up:
> - Create a Notebook Instance in SageMaker
>> - Notebook instance type : ml.t2.medium
>> - Volume Size : 5GB EBS

> - Create a role for SageMaker with the following policies:
>> - AmazonS3FullAccess
>> - AmazonRekognitionFullAccess
>> - AmazonSageMakerFullAccess



