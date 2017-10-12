# Hackend

Use it [here](http://www.hackend.xyz)
Repo for issues, bugs and requests!


## About Hackend
We set up the necessary infrastructure to get you going with a Serverless Backend. Currently, Hackend only supports provisioning resources in AWS

## How does it work?
Hackend currently only works with AWS. Here's what happens after you click deploy:
  1. We deploy either a DynamoDB Table or S3 Blob based on your selection
  2. Deploy some [boiler-plate](https://github.com/rlingineni/quickstart-aws/blob/master/s3_template.js) code
  3. Creates REST Methods for your resources and pairs the generated AWS Lambda function. Deploys the API as a v1 stage
  
  
## How much does it cost?
Hackend is free. Atleast for now, until it gets too expensive too maintain. Till then, enjoy :) Some [coffee cash](https://www.paypal.me/heyravi) is always welcome. 


  
  
  
