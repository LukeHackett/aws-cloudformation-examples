# Static Website with CloudFront Example

### Create the Website

1. Create the stack with `./bin/create-stack static-website-cloudfront`
2. Obtain the details about the deployment with `./bin/describe-stack static-website-cloudfront`
3. Add files to the bucket with `./bin/upload-to-bucket s3://BUCKET_NAME static-website-cloudfront/website` (bucket name can be found from the details of step 2)
4. Open the website (url can be found from the details of step 2)


### Destroy the Website

1. Empty the bucket with `./bin/empty-bucket s3://BUCKET_NAME` (bucket name can be found from the details of step 1)
2. Delete the stack with `./bin/delete-stack static-website-cloudfront`
