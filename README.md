# AWS Infrastructure

Basic AWS Infrastructure defined in Terraform. Includes:

- VPS with public and private subnets
- Virtual Private Gateway for VPN access
- An ECS cluster template with ELB for service discovery. An instance of this is run in both the public and private subnets, to host services either publically or privately.
- Monitoring with Cloudwatch
