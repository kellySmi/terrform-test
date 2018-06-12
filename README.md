# Terraform examples
Example files for Terraform for AWS.
## Configuration

The lambda.tf file contains the configuration to create the lambda.
this just returns a string.

The lambda-test directory contains the actual lambda JS code, this file is zipped and stored in an S3 bucket.

The api_gateway.tf contains the configuration for provisioning an API gateway, and the routes that the API define.
