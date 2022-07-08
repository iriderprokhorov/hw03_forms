# Yatube. Continue project  
## Описание изменений
- Создано и зарегистрировано приложение Core
В нём размещён и зарегистрирован фильтр addclass, позволяющий добавлять CSS-класс к тегу шаблона.
- Создано и зарегистрировано приложение about
созданы статические страницы /about/author/ и /about/tech/.
ссылки на эти страницы добавлены в навигацию сайта.
- Для всех путей установлены name и namespace
- Подключено приложение django.contrib.auth, его urls.py подключен к головному urls.py. Это было в уроке «Приложение django.contrib.auth».
- Создано и подключено приложение users, в нём Переопределены шаблоны для адресов
/auth/login/ (авторизация),
/auth/logout/ (выход из аккаунта).
- Создана страница /auth/signup/ с формой для регистрации пользователей
- В приложении posts Создана страница пользователя profile/<username>/. На ней отображаются посты пользователя. Это было в уроке «Профайл пользователя и страница записи».Создана отдельная страница поста posts/<post_id>/. Это было в уроке «Профайл пользователя и страница записи».
Подключен паджинатор, он выводит по десять постов
на главную страницу,
на страницу профайла,
на страницу группы.
- Создана навигация по разделам
 


## Системные требования
 Python3 

## Установка
- 1.clone project
- 2.install venv
- 3.install requirements
- 4.make migrations
- 5.python3 manage.py runserver

Just open browser and type 127.0.0.1:8000


## Docker

In the future

## License

MIT

**Free Software, Hell Yeah!**



