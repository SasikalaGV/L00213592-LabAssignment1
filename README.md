# CloudFormation Assignment
  Student Number: L00213592
  DevOps- 2026-2027 Lab Assignment 1

## Overview
This project demonstrates Infrastructure as Code (IaC) using AWS CloudFormation to automate the deployment of a static website and a three-tier cloud architecture.

## Project Objectives
  * Deploy a static website using Amazon S3.
  * Deploy a three-tier architecture with web, application and database tiers.
  * Apply automation, security, scalability and DevOps best practices.

## Key Technologies
  * AWS CloudFormation
  * Amazon S3
  * Amazon EC2
  * Amazon RDS
  * VPC and Security Groups
  * Git and GitHub

## Static Website Deployment
  * Host a website on S3.
  * Display the student's name and student number.
  * Configure bucket policies and website hosting settings.

## Three-Tier Architecture
  * Web Tier handles user requests.
  * Application Tier processes business logic.
  * Database Tier stores application data using RDS.

## Best Practices
  * Use reusable templates, parameters and outputs.
  * Implement least-privilege security.
  * Design for scalability and maintainability.
  * Use version control through GitHub.

## Testing
  * Validate CloudFormation stacks.
  * Verify website accessibility.
  * Confirm connectivity between tiers.

## Learning Outcomes
  * Understand Infrastructure as Code.
  * Gain AWS deployment experience.
  * Apply DevOps workflows and automation principles.

# Static S3 Website

## Tutorials used to learn the basics to run a static website using S3 bucket

I used a few basic online learning materials to understand each step of adding a static website using a YAML template. Using samples from the AWS documentation page, I slowly developed the template file step by step. Before writing the template file, I followed the lab work in AWS CloudFormation and tried launching a static website manually to learn exactly what we needed to achieve the output. That helped me write the template file step by step using samples from the AWS S3 documentation page.

After installing the AWS CLI on my machine, I created the stack for a static website and succeeded, but I still had to manually upload the index file before testing the URL. 

Basic projects:
 * https://asafmaoz.com/projects/staticwebsite.html 
 * https://medium.com/@elnala24/project-s3-static-website-with-cloudformation-2253652b7405

 S3 Cloudformation help:
 * https://docs.aws.amazon.com/AWSCloudFormation/latest/TemplateReference/aws-resource-s3-bucket.html
 * https://docs.aws.amazon.com/AmazonS3/latest/developerguide/s3_example_s3_CreateBucket_section.html

 AWS CLI docs:
 * https://docs.aws.amazon.com/cli/latest/userguide/getting-started-quickstart.html
 * https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-files.html
 * https://docs.aws.amazon.com/cli/v1/userguide/cli_cloudformation_code_examples.html#actions

 ## Results: 

 