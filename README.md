```
#!bash
pip3 install -r requirements.txt
```

* Dev-сервер (всё выполняется в папке с manage.py):
```
#!bash
python3 manage.py migrate
python3 manage.py runserver <ip:port>
```

* Для доступа к админке
```
#!bash
python3 manage.py createsuperuser
```