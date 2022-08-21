# devops-netology
Hello, World!
# Local .terraform directories
# Содержимое любого каталога репозитория, соответствующего имени .terraform (включая все его файлы и подкаталоги), будет игнорироваться
**/.terraform/*

# .tfstate files
# Игнорируются все файлы с расширением .tfstate и файлы, содержащие в имени .tfstate с любым расширением
*.tfstate
*.tfstate.*

# Crash log files
# Игнорируются файл crash.log и файлы с именем crash.* и расширением log
crash.log
crash.*.log

# Exclude all .tfvars files, which are likely to contain sensitive data, such as
# password, private keys, and other secrets. These should not be part of version 
# control as they are data points which are potentially sensitive and subject 
# to change depending on the environment.
# Игнорируются все файлы с расширением .tfvars, а также файлы с именем tfvars и расширением json
*.tfvars
*.tfvars.json

# Ignore override files as they are usually used to override resources locally and so
# are not checked in
# Игнорируются файлы override.tf, override.tf.json, а также файлы, имеющие в имени значение _override и расширение tf; и значение_override.tf и расширение json 
override.tf
override.tf.json
*_override.tf
*_override.tf.json 

# Include override files you do wish to add to version control using negated pattern
# Отслеживать файл example_override.tf, несмотря на игнорирование из предыдущего правила
# !example_override.tf

# Include tfplan files to ignore the plan output of command: terraform plan -out=tfplan
# example: *tfplan*

# Ignore CLI configuration files
# Игнорируются каталоги и файлы с именем .terraformrc, а также файл с именем terraform и расширением rc
.terraformrc
terraform.rc
