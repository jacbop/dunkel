# dunkel
Brewery Calc API

## Infrastructure
We need an S3 bucket for pipeline source code. Create a new S3 Bucket, pipeline-dunkel and a user with permissions.

Add the AWS_ACCESS_KEY_ID and the AWS_SECRET_ACCESS_KEY as secret variables to Travis.

Set env vars in Travis to access S3
```
  - S3_BUCKET=dunkel-pipeline
  - AWS_DEFAULT_REGION=us-east-2
```

## References
* https://medium.com/@tarekbecker/a-production-grade-ci-cd-pipeline-for-serverless-applications-888668bcfe04

