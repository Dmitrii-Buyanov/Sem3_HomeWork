# Инструкция по работе с git и github
> **git branch branch_name** - происходит создание ветки с именем **branch_name** 
# git commit -am "added info git branch branch_name"git 
Чтобы просмотреть список всех веток в нашем репозиторий, используем:
> **git branch** - показ всех веток в консоли
> ** git log --graph
Нажимаем Enter, пока не упремся в "END"
Выйти из END можно через "q" на англ. раскладке**
git checkout -b test
"-b" = git branch test
git branch -D test - удаление без проверки на мердж
git branch -d test - удаляет ветку test, проверив на мердж (было ли слияние или нет), если мерджа не было, удаление не произойдет
Что бы скопировать репозиторий к себе на пк используеться команда 
> **git clon URL** 
- копируеться репозиторий по адрессу **URL**
git push - это отправка изменений на github