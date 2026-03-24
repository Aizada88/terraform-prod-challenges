Steps:
terraform init
ls -la .terraform.lock.hcl

The lock file pins provider versions.
Commit it to Git so all engineers and CI use same provider builds.
