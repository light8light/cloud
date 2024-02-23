# serverless

This is a lambda function for "webapp" project.

The code has to be used with "webapp" and "awsgcp".

## Build lambda function:

The Lambda function is responsible for following:
  - Download the release from the GitHub repository and store it in Google Cloud Storage Bucket.
  - Email the user the status of download.
  - Track the emails sent in DynamoDB.
