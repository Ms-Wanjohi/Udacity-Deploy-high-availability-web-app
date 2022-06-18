PROJECT TITLE: DEPLOYING STATIC WEBSITE ON AWS.
COURSE: CLOUD DEVOPS ENGINEER.
PROJECT SUBMITTED BY: ALICE WANJOHI.

LINKS:

- S3 Bucket website endpoint: http://awanjohi.s3-website-us-east-1.amazonaws.com 
- My CloudFront distribution endpoint: https://d25bc388g6qvxj.cloudfront.net

DESCRIPTION OF SCREENSHOTS:

1. CREATED S3 BUCKET CALLED awanjohi AND UNCHECKED “BLOCK ALL PUBLIC ACCESS”.

2. UPLOADED WEBSITE FILES TO NEWLY CREATED BUCKET.
- Uploaded via the AWS Management console with Adblocker disabled to allow buysellads.svg file upload.

3. CONFIGURED IAM BUCKET POLICY TO MAKE BUCKET CONTENTS PUBLICLY ACCESSIBLE.

4. THE S3 BUCKET IS CONFIGURED TO SUPPORT STATIC WEBSITE HOSTING. WEBPAGE IS ACCESSIBLE VIA S3 BUCKET ENDPOINT URL.
- Bucket website endpoint: http://awanjohi.s3-website-us-east-1.amazonaws.com 

5. CONFIGURED CLOUDFRONT TO DISTRIBUTE STATIC WEBSITE.
- Bucket website endpoint used as the origin domain.

6. WEBPAGE IS ACCESSIBLE VIA DISTRIBUTION ENDPOINT URL: https://d25bc388g6qvxj.cloudfront.net