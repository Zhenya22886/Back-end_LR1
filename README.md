# Лабораторна робота №1


## Опис

Простий Flask-бекенд із одним endpoint `/healthcheck`.  
Проєкт запаковано в Docker і задеплоєно на Render.


## Endpoint

`GET /healthcheck`


##  Локальний запуск

```bash
python -m venv env
.\env\Scripts\Activate.ps1
pip install -r requirements.txt
flask --app app run -h 0.0.0.0 -p 8080

```
## Деплой (Render)

URL :
https://back-end-lr1.onrender.com/healthcheck

**Студент:** Сунак Євген Павлович  
**Група:** ІМ-33  