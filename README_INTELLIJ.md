# Setup for IntelliJ

This page explains how to set up your development laptop to run the workshops in the Amazon Bedrock training. 

1. Create an IAM user in an AWS account. Grant this user `Administrator' permissions. (TODO: find out what permissions we actually need)
2. Generate an access key for the user account created in step 1
3. Store the access key and secret_access_key in a file named ~/.aws/credentials
4. Set the region to `us-east-1` in your ~/.aws/config file
5. Create a new project from existing sources, point to the folder where you cloned this repo. 

Sample credentials file:

```
[default]
aws_access_key_id=ID_GOES_HERE
aws_secret_access_key=KEY_GOES_HERE
```

Sample config file:

```
[default]
region = us-east-1
```

