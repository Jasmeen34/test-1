Instructions

Step1 Install Terraform on the machine

Terraform Cloud provides infrastructure automation as a service, is free to get started, and has an in-place upgrade to paid option. We need Terraform to automate the droplet creating process
You can install Terraform by using the link below
https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli

Step2 Creating an API token

Terraform will use digital ocean API token to authenticate you. You can genereate a new API token in the API section in digital ocean. 
Next create an .env file add the token in the file

next we need to source the token by sourcing the .env file

You can verify whether it worked by using the follwoing command

Step3 Initializing Terraform
Run the following command to initialize Terraform

Step4 Clone git repository 
Next clone the git repository using the the git clone command

Step5 Make changes in the file
Next make neceesary changes in the file main.tf file according to your requirements like changing the linux distro, droplet name etc

Step6 Apply changes
Next to execute the changes run the following command
