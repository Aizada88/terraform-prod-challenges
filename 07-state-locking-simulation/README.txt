Terminal 1:
terraform init
terraform apply

While it's running, Terminal 2:
terraform apply

Local backend won't show real locks.
In production with S3 + DynamoDB locks: it prevents concurrent apply.
