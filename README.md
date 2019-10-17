# Telegram бот
## Демонстрационный проект
#### Ссылка на бота: https://t.me/VisitedPlacesBot
Создан Telegram бот. Бот развернут и опубликован на сервисе (сервере) **Heroku**. 
В работе бота использована база данных **PostgreSQL**, которая также развернута на **Heroku**.

По команде **/start** выводится текстовое сообщение с описанием его возможностей.

Бот реагирует на три команды: **/add**, **/list** и **/reset**:

- **/add** - бот пошагово опрашивает пользователя о названии места, его координатах, фотографии места
- **/list** - бот по желанию пользователя:   
    а) выводит сообщения и фото (если есть) с 10 последними добавленными местами,   
    б) выводит сообщения и фото (если есть) добавленные места в радиусе 500м (нужно будет отправить текущую локацию)   
    Оформлено в виде кнопочного меню и диалога с пользователем.
- **/reset** - бот удаляет все сохранённые данные для данного пользователя

Для помощи введите команду **/help**

Описание задачи с комментариями также здесь https://www.coursera.org/learn/python-for-web/peer/0UGyj/sozdaniie-telegram-bota