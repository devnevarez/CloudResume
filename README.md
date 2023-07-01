# CloudResume
Online Resume
A project guided by the website: https://cloudresumechallenge.dev/docs/the-challenge/aws/
This project is designed to help bridge the gap from textbook knowledge to real world knowledge. 
The project does this by demonstrating:
how code is integrated when creating a website,
running and testing code with GitHub,
the different coding languages an aspiring Cloud Engineer should familiarize themselves with to be successful,
migrating a static website to a cloud host (in this project I will be using AWS),
configuring security and navigating through AWS services to deploy a website using SSL certificates and HTTPS,
Automation using Infrastructure as Code (IAC).
The second phase of the project for me was deploying my code from this repository onto an AWS S3 Bucket.
Before I could do that though, I was to setup my AWS account. 
I read up on different best practices; mainly applying the principles of least privilege and not using the root account.
There are multiple ways to do this with AWS; which ultimately give the same result, using IAM users or AWS Organizations.
I decided to go with AWS organizations as I have not explored this functionality before.
My experience was tough with alot of reading on how to properly setup a proper structure with organizational units; it took me a little longer than I would have liked! 
Once I setup my OU, I felt confident in deploying my project, now with peace of mind that I had an added layer of security!
Thanks to my recent experiences with the Per Scholas AWS re/Start program, I felt really confident navigating the Management Console.
From this point on I just had to apply my knowledge and research (alot) on how to create my domain, attach a SSL certificate, deploy my website securely with a CloudFront distribution, and properly route my DNS records to finally get adrianscloudinitiatve.com up and running!
