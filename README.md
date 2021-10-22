# terraform_aws

```bash
brew install tfenv
tfenv install 0.13.7
tfenv use 0.13.7
terraform -version
```

Se debe crear un archivo credentials.tf con el contenido:
```terraform
provider "aws" {
  region     = "us-east-2"
  access_key = "AWS_ACCESS_KEY"
  secret_key = "AWS_SECRET_KEY"
}
```

```bash
export 
terraform init
terraform plan
terraform apply
```