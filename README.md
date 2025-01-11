# Creating a static website using terraform in AWS


## enviroment variables

To use enviroment variables with terraform you need to create a `.tfvars` file

```bash
touch terraform.tfvars
```

### Adding our AWS credentials to the terraform.tfvars file

Add the following  variables to your `.tfvars` file 

```
aws_access_key = "{your-access-key}"
aws_secret_key = "{your-secret-key}"
region = "us-east-1"
```


### Creating the terraform bucket

Run the plan command 

```bash
terraform plan
```

run the apply command

```bash
terraform apply
```

write `yes` if prompted

Your S3 bucket should be.