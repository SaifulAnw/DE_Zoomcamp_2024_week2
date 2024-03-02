Command on terraform:
```shell
# Refresh service-account's auth-token for this session
gcloud auth application-default login

# Initialize state file (.tfstate)
terraform init

# Check changes to new infra plan
terraform plan 
```

```shell
# Create new infra
terraform apply 
```

```shell
# Delete infra after your work, to avoid costs on any running services
terraform destroy
```

# You must check at the uniqe id (use your own)
