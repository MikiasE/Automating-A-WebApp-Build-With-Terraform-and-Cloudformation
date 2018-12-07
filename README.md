# Automating-A-WebApp-Build-With-Terraform-and-Cloudformation

Included Technologies: Apache, CloudFormation, MySQL, Terraform, S3

Languages: HCL (Hashicorp Configuration Language), PHP, SQL

This project demonstrates the process to build a full AWS WebApp/DB environment following AWS Security Best Practices utilizing Terraform automation (and CloudFormation as alternative). 

Project summary can be found here: 

## Prerequisites:

Install Terraform:
```
wget https://releases.hashicorp.com/terraform/0.11.10/terraform_0.11.10_linux_amd64.zip
unzip terraform_0.11.10_linux_amd64.zip
mv terraform /usr/bin/
```
Create test directory and import .tf files (I created a bucket in S3 with all .tf files, compiled into a .txt file, and used wget to pull the contents):
```
cd ~
mkdir test-tf-webapp
wget -i s3urls.txt
```

