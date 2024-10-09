# Rakib-Rifat-Portfolio
Deploying this Portfolio Website using GitHub Actions on AWS.
we need AWS S3 Bucket for this and also AWS IM credentials needed.
The main setup for this is on main.yml file.
![Screenshot 2024-10-10 010631](https://github.com/user-attachments/assets/62462a62-668d-4150-9f3d-6068fcf4af47)
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
you can have a look using this link: http://rrportfolio.s3-website-ap-southeast-2.amazonaws.com/
![Screenshot 2024-10-10 011535](https://github.com/user-attachments/assets/62589df0-f2ab-4bc7-b427-246ee8787916)
![Screenshot 2024-10-10 011550](https://github.com/user-attachments/assets/40f8f90b-92cc-40a8-9de1-e424f503bd21)
