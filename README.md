# Rakib-Rifat-Portfolio
Deploying this Portfolio Website using GitHub Actions on AWS.
we need AWS S3 Bucket for this and also AWS IM credentials needed.
The main setup for this is on main.yml file 
Here is the bucket policy for this 
"{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Sid": "PublicReadGetObject",
            "Effect": "Allow",
            "Principal": "*",
            "Action": "s3:GetObject",
            "Resource": "arn:aws:s3:::rrportfolio/*"
        }
    ]
}"
you can have a look using this link: https://us-east-1.console.aws.amazon.com/iam/home?region=ap-southeast-2#/users/details/devops-rifat?section=security_credentials
