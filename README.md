# CEA CloudFormation EC2 & ALB

## Project Overview

This project builds an Application Load Balancer (ALB) within AWS to help distribute traffic coming into a webpage, resources will eb created using AWS CloudFormation and YAML. The infrastructure is developed incrementally, with each stage documented and committed to GitHub.

The objective is to show the above process clearly, documenting each development and maintaining a clear Git history.

## Technologies

'- Amazon EC2 & ALB
'- AWS CloudFormation
'- YAML
'- Git and GitHub
'- Windows PowerShell

## Development Roadmap
Prepare - Use the existing VPC foundation: Copy over the original code for VPC, subnet, IGW, route tables and associations.
Stage 1: Create the Application Load Balancer.
Stage 2: Create Target Group to link to appropriate subnets.
Stage 3: Create the Listener for the ALB that will forward the traffic to our target group.
Stage 4: Create a Security Group for our EC2s and ALBs that enable HTTP access.
Stage 5: Create the 2 Webserver Instances defining the configuration and associations along with a bash start up script.
Stage 6: Validate the template, the Instances and AutoScaling Group works.

## Repository Structure
templates/ec2.yaml - CloudFormation ec2 template. docs/development-log.md - Developments and implementation notes.

## Status
In development. Resources are introduced and documented with each development stage.

## Security Considerations
Consider the impact of networking permissions and protocols when creating any resources that connect to the internet. For production keep in mind Principle of least priviledge in everything you do.

The project is for demonstration purposes only. Review all networking permissions before deployment.