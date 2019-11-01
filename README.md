# cloudformation-base-enclave
This is a base enclave including a VPC with associated components, EC2 instances, and other requirements for a general web application

Started with the "A single Amazon EC2 in an Amazon VPC" found here and then adapted it to my needs: https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/sample-templates-services-us-west-2.html#w2ab1c23c58c13c41

Use the following command to generate a list of security group rules in JSON format: aws ec2 describe-security-groups | clip

NACLs: ec2 describe-network-acls

Tools: VS Code plus CloudFormation plugin. Shift+Alt+F to format after adding a snippet.
