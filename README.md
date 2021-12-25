# README

## Git flow

### Lesson

- начался урок
- переключаемся на ветку main
    ```
    git checkout main
    ```
- подтягиваем актуальное состояние репозитория
    ```
    git pull
    ```
- создаём ветку урока
    ```
    git checkout -b lesson_n
    ```
- выполняем все задания урока
- в конце урока
- индексируем изменения
    ```
    git add .
    ```
    ```
    git add ./lesson/my-file.js
    ```
- коммитим изменения
    ```
    git commit -m "lesson_n"
    ```
- пушим изменения в удалённый репозиторий
    ```
    git push --set-upstream origin lesson_n
    ```
- переходим в GitHub
- переходим на вкладку pull request
- жмём кнопку new pull request
- проверяем базовую ветку base: main
- устанавливаем ветку которую желаем смёрджить compare: lesson_n
- жмём кнопку Create pull request
- указываем комментарий к мру
- мёрджим нажав кнопку Merge pull request

### Homework

- приступаем к выполнению дз
- переключаемся на ветку main
    ```
    git checkout main
    ```
- подтягиваем актуальное состояние репозитория
    ```
    git pull
    ```
- создаём ветку дз
    ```
    git checkout -b homework_n
    ```
- выполняем все задания дз
- индексируем изменения
    ```
    git add .
    ```
    ```
    git add ./homework/my-file.js
    ```
- коммитим изменения
    ```
    git commit -m "homework_n"
    ```
- пушим изменения в удалённый репозиторий
    ```
    git push --set-upstream origin homework_n
    ```
- переходим в GitHub
- переходим на вкладку pull request
- жмём кнопку new pull request
- проверяем базовую ветку base: main
- устанавливаем ветку которую желаем смёрджить compare: homework_n
- жмём кнопку Create pull request
- указываем комментарий к мру
- сообщаем о выполнении дз
- при получении замечаний в комментариях к мру вносим исправления в код
(обратите внимание что правки нужно вносить в той ветке в которой
выполнено дз, при необходимости на эту ветку нужно переключиться
    ```
    git checkout homework_n
    ```)
- индексируем изменения
    ```
    git add .
    ```
    ```
    git add ./homework/my-file.js
    ```
- коммитим изменения
    ```
    git commit -m "homework_n"
    ```
- пушим изменения в удалённый репозиторий
    ```
    git push --set-upstream origin homework_n
    ```
- после решения всех замечаний и получения апрува мёрджим нажав кнопку
merge pull request


Урок 1 Д/з
1. Реализовать html-страницу
2. Сделать заголовок "Домашнее задание урока 1"
3. Отдельно в абзацах реализовать многострочный текстовый контент
4. Нумерованный список порядка изучения технологии фронтенда и ненумерованный список перечня технологий фронтенда 
5. Каждый пункт списков должен именть в себе ссылку на статью по технологии
Разработку вести в отдельной ветке репозитория с уроками по HTML

Урок 3 Д/З
1. Реализовать html-документ по всем правилам семантики, который будет состоять из 3х страниц
1.1. первая страница - 3 статьи объединённые в секцию
1.2. вторая страница - 1 статья разделённая на параграфы
1.3. третья страница - html-форма с любым количеством полей
для реализаци д/з необходимо изучить тег <form action=""></form>