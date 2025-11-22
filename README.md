# devops-netology
# студент: Колыванов Антон

Репозиторий в рамках курса - Системы управления версиями  


проверка
1
2
3
4
5
6
v.0.0.1-rc
#какие файлы будут проигнорированы в будущем благодаря добавленному .gitignore

```
.terraform/   все файлы внутри этой папки

*.tfstate   все файлы  в папке terraform и подпапках с расширением tfstate
*.tfstate.*  все файлы в папке terraform и подпапках с любым именем и   расширением после расширения .tfstate


crash.log  файл в папке terraform
crash.*.log   файлы crash с любым текстом между crash и .log

*.tfvars все файлы в папке terraform и подпапках с расширением tfvars
*.tfvars.json все файлы в папке terraform и подпапках с расширением tfvars.json

override.tf файл в папке terraform
override.tf.json файл в папке terraform 
*_override.tf   любой файл в папке terraform и подпапках  заканчивающийся на _override.tf
*_override.tf.json  файл в папке terraform любой файл в папке terraform и подпапках  заканчивающийся на _override.tf.json

.terraform.tfstate.lock.info файл в папке terraform 

.terraformrc файл в папке terraform
terraform.rc файл в папке terraform
```

