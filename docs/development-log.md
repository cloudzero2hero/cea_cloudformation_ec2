# Development Log

## Stage 1 - VPC Foundation & Creation of Application Load Balancer

### Implemented
- Created the initial VPC CloudFormation template using previous VPC code.
- Create the Application Load Balancer.

### Outstanding
- Create Target Group to link to appropriate subnets.
- Create the listener for the ALB that will forward the traffic to our target group.
- Create a security group for our EC2s and ALBs that enable HTTP access.
- Create the 2 Webserver Instances defining the configuration and associations along with a bash start up script.
- Validate the template, the Instances and AutoScaling Group works.

### Validation
- Pending CloudFormation template validation.
- Deployment not yet performed.

## Stage 2 - Target Group Creation

### Implemented
- Create Target Group to link to appropriate subnets.

### Outstanding
- Create the listener for the ALB that will forward the traffic to our target group.
- Create a security group for our EC2s and ALBs that enable HTTP access.
- Create the 2 Webserver Instances defining the configuration and associations along with a bash start up script.
- Validate the template, the Instances and AutoScaling Group works.

### Validation
- Pending CloudFormation template validation.
- Deployment not yet performed.