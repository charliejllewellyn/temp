# Pre-reqs
VPC with private subnets and no IGW or NAT
VPCE for Glue and S3
Windows Bastion

# Deployment
Run the CloudFormation script supplying the parameters requested

# Testing
Login to the Windows bastion and access Hue via http://<master EMR private hostname>:8888

Access the Presto engine, databases from Glue should be listed. Test querying one of the databases.
