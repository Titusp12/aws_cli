#### CLI to work with S3
  * aws config
  (press enter enter on all)
  * aws s3 mb s3://bucketname --create a bucket
  * aws s3 ls --check your bucket
  * aws s3 rb s3://bucket_name --force  --delete a bucket
#### Move file to s3
  * aws s3 cp (file_to_migrate) s3://(bucket_name) --moves file to desired s3 bucket.
  
#### Working with EC2
  * aws ec2 describe-instances --- to see if it works correctly
  * aws ec2 describe-instances --output table
  * aws ec2 describe-instances --output text
  * aws ec2 describe-instances --output json
  * aws ec2 run-instances --image-id  ami....... --count 2 --instance-type t2.micro --key-name ......  --security-groups .......
  *  aws ec2 describe-instances | grep InstanceId
  * aws ec2 create-key-pair --key-name MyKeyPair --query 'KeyMaterial' --output text > MyKeyPair.pem
  * aws ec2 run-instances --image-id ami-8c1be5f6 --instance-type t2.micro --key-name MyKeyPair

