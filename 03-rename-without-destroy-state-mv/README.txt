Steps:

1) terraform init
2) terraform apply

3) Rename resource in code:
   local_file.old_name -> local_file.new_name

4) terraform plan  (it will show destroy/create)

Correct fix:
terraform state mv local_file.old_name local_file.new_name

Then:
terraform plan
terraform apply
