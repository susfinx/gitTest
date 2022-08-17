# Git Commands Memo

## Основные команды:

* Добавить некоторые изменения в <файле> в следующий коммит

        git add -A


* Создать новую ветку на основе текущей HEAD

        git checkout <ветка>

* Переименовать текущюю ветку

        git branch _M <new_name>


* Удалить ветку

        git branch -d <branch_name>

* Установить связь с удаленным репозиторием

        git remote add origin <url>

* Обновить ветку удаленного репозитория

        git push -u origin <branch_name>

* Обновить ветку локального репозитория c cthdt

        git pull origin <branch_name>