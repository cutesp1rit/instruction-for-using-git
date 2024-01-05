#Инструкция по пользованию гитом
### 1. Инциализируем репозиторий
Для этого есть команда ``` git init ```  <br>
**Разгитить** можно удалив папку .git, то есть ``` rm -rf .git```  <br>
### 2. Подготовка к сохранению и коммит
Для этого используем команду ``` git add ```  и название файла с расширением. <br>
Еще можно использовать ``` git add --all```  или ``` git add . ```  (добавит всю папку) <br>
Для проверки статуса: ```git status```  <br>
Коммит делается так: ``` git commit -m 'Здесь сообщение к нему' ``` <br>
Чтобы посмотреть историю коммитов: ``` git log ```  <br>
### 3. Привязка и синхронизация удаленного репозитория к локальному
Для начала входим в папку с репозитрием, который хотим привязать <br>
Вводим в git bash: ```  git remote add origin git@github.com:%ИМЯ_АККАУНТА%/first-project.git  ```  <br>
** Важно, чтобы был выбран SSH, а не HTTPS ** <br>
Чтобы убедиться, что репозитори связаны: ``` git remote -v ```  <br>
Для синхронизации используем команду: ``` git push -u origin master ```  (в дальнейшем будет достаточно get push) <br> 