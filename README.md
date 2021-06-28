# Regulated Development AWS
Regulated Development on AWS

# Motivation
We have all created an Instance where we deploy it for production but in the real world, there are many stages of development including testing, staging, and development. In this post, I will be creating a scalable production server with development and testing servers locked inside a private IP and scheduling using AWS Instance Scheduler.

# Architecture
![architecture](https://user-images.githubusercontent.com/13358738/123626496-a4cf2200-d830-11eb-8eee-8cb9bb60911c.png)

# Prerequisites:
1. AWS EC2
2. AWS AMI
3. AWS Cloudfomration
4. AWS VPC
5. AWS Auto Scaling
6. AWS Load Balancer
7. AWS Route53

# Replication Steps
1. As the wordpress ami on the Marketplae, we will be using that on development
2. All the steps are written in the blog post
