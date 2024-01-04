# Description of main commands

* git init - initialisation of repository
* git status - check status of repo
* git add - save changes
* git commit - apply changes to repo
* git remote add origin 'ssh key'
* git push - send changes to remote repo
---
# Hash, logs, status, commits

* Хэш - хранит основную информацию о авторе коммита, дате и содержимого закомиченных файлов. Все хэши хранятся
в папке .git репозитория. Преобразуется хэш с помощью алгоритма SHA-1. Увидеть его можно набрав `git log`.

* Можно вызвать не только полный лог, но и сокращённый — это делается командой `git log --oneline`. В сокращённом логе выводятся сокращённые хеши — их можно использовать точно так же, как и полные.
В самом логе содержится: хэш, автор, дата, сообщение коммита.
