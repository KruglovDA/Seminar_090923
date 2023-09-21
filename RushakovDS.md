# Краткое руководство по Git
## Что такое Git?
Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локаальные, так и удалённые репозиториию. Является самой популярной реализацией систем контроля версий в мире.

## Подготовка репозитория
Для создание репозитория необходимо выполнить команду *git init* в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

## Создание коммитов

### Git add
Для добавления измений в коммит используется команда ***git add***. Чтобы использовать команду *git add* напишите *git add <имя файла>*

### Просмотр состояния репозитория
Для того, чтобы посмотреть состояние репозитория используется команда *git status*, и Вы увидите были ли изменения в файлах или их не было.

## Работа с ветками
git branch name - создать ветку
git branch - выводит список веток
git delete name - удалить ветку

### Выбор ветки
git chekout name_branch - для выбора ветки, в которой хотим работать 

### Просмотр ветки, в виде древа
git log --graph - в терминале, справа, будет разделение линии в виде разделение на полосу дорог

### Слияние
git merge name - слияние выбраной ветки, в основную. Основная ветка часто будет master или main.

прим(дальше буду писать на английском, чтобы лучше и быстрее усвоить технический английский)
## Work with GitHub

git clone - moving on  website GitHube in order to do copy information through the function fork in local file.

git pull - this command it is needed  in order to extract and download content from a remote repository and update the local repository with this content.

git push - this command it is needed in order to local repository with this content sent to remote repository to download a file
