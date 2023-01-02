# NotesApp_React_Django
## Создание онлайн-заметок на React и Django
*Все команды выполняются на Windows*

--> Переключиться на папку, где лежат все файлы проекта:
```
cd NoteApp_React_Django
```
--> Создать виртуальную среду:
```
virtualenv env
```
--> Активировать виртуальную среду: 
```
.\env\Scripts\activate
```
--> Запуск сервера /порт 3000/ (React):
```
npm start
```
--> Запуск сервера /порт 8000/ (Django):
```
python manage.py runserver
```
--> Что нужно сделать перед запуском:
1. Скачать Node.js

  *Node. js — среда выполнения кода JavaScript вне браузера, которая позволяет писать серверный код для веб-страниц и веб-приложений, а также для программ командной строки. С помощью Node. js реализуется парадигма «JavaScript для всего».*

2. Установить router dom version 5.3.0
```
npm install -s react-router-dom@5.3.0
```
