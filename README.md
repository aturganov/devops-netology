Это промежуточная директория(любой глубины вложенности от текущей) - **/.terraform/*
И, соотвественно, будут игнорированы все файлы, входящие в директорию

Добавлены коммиты:
- test1
- add fix branch 
- work with pycharm

*.tfstate - Будут игнорированные файлы с расширением tfstate
*.tfstate.*  Будут игнориванны файлы с промежуточным расширением .tfstate. 

Будет игнорирован файл лога  - crash.log

*.tfvars - Игнориванный файлы с расширением tfvars

игнорированные файлы override.tf override.tf.json, 
а также содержащие в названии override.tf и override.tf.json 
*_override.tf
*_override.tf.json

Будет игнорирован CLI конфигурационный файл  - .terraformrc, а такеж terraform.rc

