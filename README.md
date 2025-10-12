# devops-netology
devops-netology
Modify
# .gitignore в корне пустой
####### BEGIN Terraform.gitignore

# Local .terraform directories
.terraform/

# .tfstate files
*.tfstate # Все что заканивается на .tfstate
*.tfstate.* # Все что содержит в названии подстроку .tfstate.

# Crash log files
crash.log # Файл с таким названием
crash.*.log # Файл начинающийся на crash. и  заканчивающийся на .log

# Exclude all .tfvars files, which are likely to contain sensitive data, such as
# password, private keys, and other secrets. These should not be part of version
# control as they are data points which are potentially sensitive and subject
# to change depending on the environment.
*.tfvars # Все что заканивается на .tfvars
*.tfvars.json # Все что заканивается .tfvars.json

# Ignore override files as they are usually used to override resources locally and so
# are not checked in
override.tf # Файл override.tf
override.tf.json  # Файл override.tf.json
*_override.tf  # Все что заканивается на *_override.tf
*_override.tf.json  # Все что заканивается на _override.tf.json

# Ignore transient lock info files created by terraform apply
.terraform.tfstate.lock.info  # Файл .terraform.tfstate.lock.info

# Ignore CLI configuration files
.terraformrc # Файл .terraform.rc
terraform.rc # Файл terraformrc

####### END Terraform.gitignore

new line
