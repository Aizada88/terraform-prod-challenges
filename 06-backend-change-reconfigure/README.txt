Production behavior:

If backend config changes:
terraform init -reconfigure

If moving state to a new backend:
terraform init -migrate-state
