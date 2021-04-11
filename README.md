          # e2 - email_out #

Отправка email по адресу с текстом и выдержкой

  * Отправка через sendgrid.com *
  

python -m venv env

env\Scripts\activate.bat

pip install -r requirements.txt

python manage.py migrate

setx SENDGRID_API_KEY <ключ API>

setx SENDGRID_TEMPLATE_ID <id шаблона письма>

setx SENDGRID_FROM <поле From письма>

python manage.py runserver

http://127.0.0.1:8000/
