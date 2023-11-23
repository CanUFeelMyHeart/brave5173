+7-999-888-77-66
# Инструкция по связке Git - GitHub

Чтобы склонировать репозиторий к себе на ПК, используется команда: 
> **git clone URL** - клонируется репозиторий по адресу **URL** 

* *git push - синхронизировать из локального в удаленный репозиторий 
* *git push origin <branch_name> - отправить локальную ветку <branch_name> в репозиторий origin
* *git push origin --delete <branch_name> - удаление ветки <branch_name> из удаленного репозитория github origin
* *git push origin :<branch_name> - удаление ветки <branch_name> из удаленного репозитория github origin
* *git pull - загрузка с gitgub.com обновлений вместе со сливанием веток
* *git remote rename <name> - переименовать удаленный репозиторий на <name>
* *git remote remove <name> - удалить удаленный репозиторий с именем <name>
* *git remote - список настроенных удалённых репозиториев
* *git remote -v - просмотреть адреса для чтения и записи, привязанные к репозиторию
* *git remote add <name> <url> - добавить удалённый репозиторий по ссылке <url> и присвоить ему имя <name>
* *git fetch [remote-name] - для получения данных из удалённых проектов