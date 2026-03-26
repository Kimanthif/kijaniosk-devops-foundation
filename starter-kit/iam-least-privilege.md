# IAM Least Privilege Policy

## Task
The application needs to fetch product images from the S3 bucket `kijaniosk-product-assets`.

## Policy
This policy grants only the minimum needed permissions:

```json
{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Effect": "Allow",
      "Action": ["s3:GetObject"],
      "Resource": "arn:aws:s3:::kijaniosk-product-assets/*"
    }
  ]
}