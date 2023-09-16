# **Руководство по GIT**
## 1. Основные команды
* git init - создает репозиторий.
* git status - выводт информацию о состоянии репозитория
* git add - начинает слежение за новыми файлами
* git commit - фиксация изменений
* git diff - показать разницу между версиями
### 1.1 сокращение команд
* git commit -am "_коментарий к изменению_" - коменда для начала слежения и фиксации изменений (add + commit)

## 2. Работа с ветками
* git branch - выводит список веток
* git branch branch_name - создает ветку с именем braunch _name
* git log - выводит журнал изменений.
* git log --graph - выводит журнал в виде графика.
* git checkou branch_name - переход к ветке braunch_name.
* git merge branch_name - слияние с веткой braunch_name.
* git branch -d branch_name - удаление ветки.
* git reset --hard HEAD~ - удаление слежения до слияния веток.
* git checkout -b branch_name - создание и переход в новую ветку branch_name.
## 3. Работа с даленным репазиторием
* git clone - клонирование репазитория.
* git pull - 
* git push - .