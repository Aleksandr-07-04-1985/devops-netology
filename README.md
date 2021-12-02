# devops-netology
# Будут игнорироваться все файлы в папке .terraform
**/.terraform/* 
# В первом примере игнорируются все файлы с любыми символами заканчивающиеся на .tfstate(пример name.tfstate) во втором все файлы в которых есть слово .tfstate.( пример name.tfstate.name)
*.tfstate
*.tfstate.*
# Будет игнорироваться только этот файл
crash.log
# Будут игнорироваться все файлы с любыми символами заканчивающиеся на .tfvars
*.tfvars
# будет игнорироваться только этот файл override.tf и override.tf.json
# Будут игнорироваться все файлы с любыми символами заканчивающиеся на _override.tf и _override.tf.json
override.tf
override.tf.json
*_override.tf
*_override.tf.json
# будет игнорироваться только этот файл .terraformrc и terraform.rc
.terraformrc
terraform.rc