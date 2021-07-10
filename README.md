# AWS Serverless getSignedURL monorepo

## Overview

This project is made for the Reutlingen University course `Cloud and Big Data Technologies`.
The research topic is: `Serverless Computing mit AWS Lambda`.

This project is a monorepo with two packages:

- The `Vue` Frontend in `/packages/frontend` containing the index.html, adopted from https://github.com/aws-samples/amazon-s3-presigned-urls-aws-sam.

- The `AWS-Lambda` Backend in `/packages/backend` working with the Serverless Framework CLI.

## Steps to reproduce the deployment with the Serverless Framework CLI

```
- npm install -g- serverless
- serverless config credentials --provider aws --key YOUR_ACCESS_KEY --secret YOUR_SECRET_KEY --profile serverlessUser
- sls deploy
```