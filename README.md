# aws-ec2-portfolio-project
Launched and configured an EC2 instance with EBS storage and tagging on AWS
# AWS EC2 Instance with EBS Storage & Tagging

## Project Overview
Launched a cloud server on AWS using EC2, attached a separate 
EBS storage volume, and applied a production-style tagging strategy 
for cost tracking and governance.

## Services Used
- Amazon EC2 (t2.micro, Amazon Linux)
- Amazon EBS (8 GiB gp3 volume)
- AWS Tagging Strategy

# What I Did
- Launched an EC2 instance named `web-server-dev`
- Attached a secondary 8 GiB EBS volume for separate data storage
- Applied tags: Environment, Project, and Owner
- Practiced proper instance lifecycle management (start/stop)

# Tags Applied
| Key         | Value          |
|-------------|----------------|
| Environment | dev            |
| Project     | my-portfolio   |
| Owner       | [Your Name]    |

# Screenshots
(See screenshots folder below)

# What I Learned
- How to launch and configure an EC2 instance in the AWS Console
- Why separate EBS volumes are used in production environments
- How tagging helps teams track costs and ownership in real companies
