# DesSecOps_AWS


The setting up of an project with Autoscaling included the AWS CloudFront, AWS CloudWatch and AWS Elastic Beanstalk. A stress test was applied to test the Autoscaling of instances, when the CPU utilization trigger the max limit set up, the CloudWatch takes an action of alert trough SNS and Slack message directly to the DevOps team.  

## Table of Contents

- Static Website
- Python application 
- requeriments 
- DynamoDB
- CloudWatch reports integrated with Slack / SNS
- Running AWS commands from Slack to E2 instances 

## Use Cases

- Migration of static Websites or Application from on-premisses to AWS Cloud environment. 
- Cloud project focused on in a situation where the application has required a high demand of CPU and RDS.     

## Commands

On Bash file:
- touch /var/app/file
- sudo chown -R webapp:webapp /var/app/*

### Version 1.0
