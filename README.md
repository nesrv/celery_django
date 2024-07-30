# Demo project Celery + Django + Docker

## [YouTube](https://www.youtube.com/channel/UC_hPYclmFCIENpMUHpPY8FQ)

### Первый запуск

- docker-compose up --build

### Последующие запуски

- docker-compose up


## for me

### Linux

```sh
sudo apt install python3.11-venv
python3 -m venv celery_venv
source celery_venv/bin/activate
pip install -r requirements.txt 
python3 manage.py runserver

```


### celery

```sh
celery -A send_email worker -l info
```


```sh
git remote rm origin
git remote add origin https://github.com/nesrv/celery_django.git

```




```sh
ssh -T git@github.com
```