# DesSecOps_AWS

The setting up of instances to install automatically a Security Agent through AWS SystemsManager. The Run Command component has been used to install automatically this agent and the DevSecOps Engineer will be notified through the Amazon Simple Notification Service.

## Table of Contents

- Terraform: main and provider
- Security agent 
- Bash commands (Session Manager - AWS)
- SNS - Amazon Simple Notification Service


## Use Cases

- Migration of static Websites or Application from on-premisses to AWS Cloud environment. 
- Cloud project focused on in a situation where the application has required a high demand of CPU and RDS.     

## Commands

On Bash file:
- touch /var/app/file
- sudo chown -R webapp:webapp /var/app/*

### Version 1.0
