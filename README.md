# static-website
Deploy Static Website on AWS

### Website Files
- [s3-bucket.png](https://github.com/nhothuy48cb/static-website/blob/main/s3-bucket.png) - The S3 bucket is created.
- [website-files.png](https://github.com/nhothuy48cb/static-website/blob/main/website-files.png) - All the website files uploaded to the newly created S3 bucket.
- [static-website-hosting.png](https://github.com/nhothuy48cb/static-website/blob/main/static-website-hosting.png) - The S3 bucket is configured to support static website hosting.
- [public-iam-policy.png](https://github.com/nhothuy48cb/static-website/blob/main/public-iam-policy.png) - The S3 bucket has an IAM bucket policy that makes the bucket contents publicly accessible.

### Website Distribution
- [cloud-front.png](https://github.com/nhothuy48cb/static-website/blob/main/cloud-front.png) - CloudFront has been configured to retrieve and distribute website files.

### Web Browser Access
- CloudFront domain name URL: https://d38b9xsf1tcdyz.cloudfront.net/
- website-endpoint URL: http://my-658942388635-bucket.s3-website-us-east-1.amazonaws.com/