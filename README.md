# Deploying-the-project-on-AWS
Deploying a Node Js Application on AWS EC2
Node.js Application Deployment on AWS EC2 is a step-by-step technical blueprint and boilerplate repository that demonstrates how to successfully deploy and configure a full-stack Node.js web application in a production cloud environment using Amazon Web Services (AWS).
Key Implementations & Cloud Architecture
• Cloud Infrastructure (IaaS): Provisioned and managed a virtual server using an AWS EC2 instance running an Ubuntu Linux OS (t2.micro tier).
• Identity & Access Management (IAM): Implemented AWS security best practices by setting up dedicated IAM users with scoped admin privileges.
• Network & Security Configuration: Configured AWS Security Groups to manage inbound/outbound traffic rules, allowing public access strictly through specified application ports (Port 3000).
• Static Domain Routing: Allocated and attached an AWS Elastic IP Address to the EC2 instance, providing the application with a persistent, unchanging public domain.
• Secure Remote Access & Deployment: Utilized SSH with a private key pair (.pem file) to securely access the remote server, update system dependencies, pull repository assets via Git, and initialize production dependencies using NPM.

