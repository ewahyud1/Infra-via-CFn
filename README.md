# Infra-via-CFn
Provision AWS infrastructure using CloudFormation template

## windows-ec2
This CFn template creates an EC2 with Windows OS. It contains a metadata section that has Powershell scripts which will be executed during the bootstrap process.  This allows pre-loading of any software and/or enabling Windows features/services.

## network-load-balancer
This CFn template creates a public facing network load balancer (NLB), an Alias Route53 zone record from an existing Hosted Zone; to the NLB.
