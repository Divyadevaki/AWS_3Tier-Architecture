# AWS_3Tier-Architecture
Complete document of Deploying web application in Three-Tier Architecture project.

•	Implementing Three-Tier design that separates Web-Tier, App-Tier and DB-Tier using EC2, ALB.
•	S3 for Application Storage, Adding S3ReadOnly policy in EC2 instance using IAM.
•	Configuring the RDS database for inserting the records.
•	Installing MySQL, Node.js, Pm2 Process manager in App-tier and node-modules, Nginx server in Web-tier
•	Creating the Security group rules using Private subnet inside VPC which enables the Cloud user should communicate with Application only through the Jump Server.
•	Enabling SSL Certification using ACM for Secure connection.
•	Configured Auto Scaling for high availability. Route 53 for translating domain name into IP Address, CloudFront for caching static content in global network of edge locations.
