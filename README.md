# devops-netology
#v0.1
My name is Evgeny

#будут игнорироваться файлы во всех вложенных каталогах .terraform
**/.terraform/*

# будут игнорироваться файлы с расширением .tfstate
*.tfstate

# будут игнорироваться файлы подходящие под шаблон любые_символы.tfstate.любые_символы 
*.tfstate.*

# будет игнорироваться файл crash.log
crash.log

# будут игнорироваться файлы с расширением .tfvars
*.tfvars


# будут игнорироваться файл override.tf
override.tf

# будут игнорироваться файл override.tf.json
override.tf.json

# будут игнорироваться файлы вида любые_символы_override.tf и любые_символы_override.tf.json
*_override.tf
*_override.tf.json

#будет игнорироваться скрытый файл .terraformrc
.terraformrc

# будет игнорироваться файл terraform.rc
terraform.rc
