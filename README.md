# Terraform examples
Exploring Terraform for AWS.

## File Explanation

The lambda.tf file contains the configuration to create the lambda.
This returns a string.

The lambda-test directory contains the actual lambda JS code, this file is zipped and stored in an S3 bucket.

The api_gateway.tf contains the configuration for provisioning an API gateway, and the routes that the API define.

the API routes are
* /api/gettrue method=GET
  returns JSON string {"success": "true"}
* /postTest method=POST
