# devops-netology
Hello, World!

#### Содержимое любого каталога репозитория, соответствующего имени .terraform (включая все его файлы и подкаталоги), будет игнорироваться
**/.terraform/*

#### Игнорируются все файлы с расширением .tfstate и файлы, содержащие в имени .tfstate с любым расширением
*.tfstate
*.tfstate.*

#### Игнорируются файл crash.log и файлы с именем crash.* и расширением log
crash.log
crash.*.log

#### Игнорируются все файлы с расширением .tfvars, а также файлы с именем tfvars и расширением json
*.tfvars
*.tfvars.json

#### Игнорируются файлы override.tf, override.tf.json, а также файлы, имеющие в имени значение _override и расширение tf; и значение_override.tf и расширение json 
override.tf
override.tf.json
*_override.tf
*_override.tf.json 

#### Отслеживать файл example_override.tf, несмотря на игнорирование из предыдущего правила
!example_override.tf

#### Игнорируются каталоги и файлы с именем .terraformrc, а также файл с именем terraform и расширением rc
.terraformrc
terraform.rc
