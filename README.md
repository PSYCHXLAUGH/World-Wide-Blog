# Для проверки
- python3 -m virtualenv env
- source env/bin/activate
- pip install -r requirements.txt
- manage.py makemigrations paper
- manage.py migrate paper
- manage.py migrate
- manage.py createsuperuser
- manage.py runserver
- переходим по адресу 127.0.0.1/admin/ и авторизируемся в админке
- добавляем категории
- окончательный запуск в режиме отладки manage.py runserver
![result](https://github.com/PSYCHXLAUGH/WWB/blob/main/demo.png)
