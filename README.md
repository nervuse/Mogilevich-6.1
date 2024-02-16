# Mogilevich-6.1

[Проект SqlVerifier](https://github.com/IT-switcher/verifier) (развернут в контейнере Doker)
### Чтобы использовать мою коллекцию для Postman, выполни следующие шаги:

1. В постман во вкладке APIs нажми "Create an API"
2. Выбери подключение к "GitHub", и в браузере нажми "Continue"
3. В Postman на страничке "Connect your GitHub repository" выбери организацию "nervuse", репозиторий "Mogilevich-6.1" и ветку main. Далее нажми кнопку "Connect Repository"
4. Скачай Download.zip через зеленую кнопку <>Code этого репозитория к себе на ПК и разархивируй. Добавь в Postman файл **sqlverifiver.postman_environment.json** - это окружение. А файл **MogilevichDZ5.2.csv** - это тестовые данные для прогона коллекции
5. Готово. Используй и не забывай пушить изменения!

### Использование переменных:
- В файле **workspace.postman_globals.json** содержится базовый url проекта, используется в запросах
- В файле **sqlverifiver.postman_environment.json** содержатся переменные «id» (значение автоматически сохраняется в переменную после отправки POST запроса «create task») и токен авторизации (который нужно обновлять с новой сессии проекта  SqlVerifier из DevTools)
- В самой коллекции есть переменные «text», «answer», «title» которые можно менять в ручную, если необходимо отправить запрос вручную без тестового файла *.csv*
- В запросах во вкладке «Pre-request Script» имеется скрипт созданных локальных переменных, которые можно менять в ручную, если необходимо отправить запрос вручную без тестового файла *.csv*
