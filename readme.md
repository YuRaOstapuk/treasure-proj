# Treasure proj

### Workflow tutorial

### Начало работы
1. Cо своего аккаунта сделать fork
2. Склонировать СВОЙ репозиторий к себе
3. npm i (установить пакеты)
4. Создать переменные ссылки на репозитории (origin и masterrep) 
`git remote add origin |ссылка на свой реп|`
`git remote add masterrep |ссылка на мастер реп|`


### Работа над задачей

1. Проверяем на какой ветке мы находимся `git branch`
2. Переходим на главную ветку `git checkout main`;
3. Освежаем обновлениями наш main `git pull masterrep main`;
4. Создаем ветку над которой будет работать `git checkout -b |название ветки|`
5. Пишем код
6. Коммитим `git add .` `git commit -m 'commit message'`
7. Пушим ветку к СЕБЕ в репу `git push origin |название вашей ветки|`
8. Идем в браузер в СВОЙ репозиторий
9. Создаем пулл реквест в main ветку master репозитория



