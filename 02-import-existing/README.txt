Steps:

1) Create file first (outside Terraform):
   echo "i already existed" > existing.txt

2) terraform init

3) Import it into state:
   terraform import local_file.import_me existing.txt

4) terraform plan

Key point:
Import updates Terraform STATE. After import, ensure Terraform code matches reality.
