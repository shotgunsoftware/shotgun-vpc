# Shotgun Private Cloud AWS CloudFormation templates

The latest version are available on direct on S3, see link below.

| Template      | Description |
| ------------- | ------------- |
| [Private S3 bucket](https://sg-shotgunsoftware.s3-us-west-2.amazonaws.com/tier1/cloudformation_templates/sg-private-s3-bucket.yml) | Create a S3 Bucket and associated IAM Role for Shotgun to access it. |
| [Private VPC](https://sg-shotgunsoftware.s3-us-west-2.amazonaws.com/tier1/cloudformation_templates/sg-private-vpc.yml) | Create a private VPC to host a private S3 proxy. | 
| [Private S3 proxy](https://sg-shotgunsoftware.s3-us-west-2.amazonaws.com/tier1/cloudformation_templates/sg-s3-proxy.yml) | Create a S3 proxy service running on Fargate in an existing VPC. | 
| [Public VPC](https://sg-shotgunsoftware.s3-us-west-2.amazonaws.com/tier1/cloudformation_templates/sg-public-vpc.yml) | Create a VPC with private and public subnets to host a S3 public proxy. | 
| [Public S3 proxy](https://sg-shotgunsoftware.s3-us-west-2.amazonaws.com/tier1/cloudformation_templates/sg-s3-proxy-public.yml) | Create a public S3 proxy service running on Fargate in an existing VPC. |