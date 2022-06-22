# SocialNetwork

## Социальная сеть на Django
### Start
#### Локально, сервер разработчика

<code>python manage.py runserver</code>

#### Для сохранения изображений (jpg, jpeg, png):

http://localhost:8000/images/create/?url=<Ссылка_на_изображение>


#### Чтобы букмарклеты работали с HTTPS, необходимо использовать Ngrok:

https://ngrok.com/

#### Необходимо создать .py файл с данными для  использования SMTP (В данном проекте использовался mail.ru).

Смотри data_dict_example.py.

#### Cайт администрирования:

python manage.py createsuperuser

http://localhost:8000/admin/
