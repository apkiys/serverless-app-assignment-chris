# serverless-app-assignment-chris
Assignment 3.7 for Chris

Three *.txt files were uploaded to the S3 bucket created by terraform.
SQS received messages of the upload as below:

![image](https://github.com/apkiys/serverless-app-assignment-chris/assets/20112494/4a1a681b-4b6a-4320-bb46-5b3524a8887c)

The files uploaded successfully as shown:
![image](https://github.com/apkiys/serverless-app-assignment-chris/assets/20112494/b2542cdb-3ea5-4169-8ebe-27cbc4a8f775)

Through the following commands:<br />
aws s3 cp file_to_upload_1.txt s3://serverless-app-assignment-chris/ --region "ap-southeast-1"<br />
aws s3 cp file_to_upload_2.txt s3://serverless-app-assignment-chris/ --region "ap-southeast-1"<br />
aws s3 cp file_to_upload_3.txt s3://serverless-app-assignment-chris/ --region "ap-southeast-1"<br />
