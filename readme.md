## This is a Simple Blood Bank Management System based on Python Django
# Tools or Languages used-

Python

HTML

CSS

Javascript

Django

SQLite3


# My project as name suggest is a blood bank management system which also includes blood compatibility rules, gender specific modifications, blood bag size standards and all basic features a blood bank management system should have. Future work- Proper Authentication System, Proper Multi-Instance Support, User authentication based on Adhaar, More Beautiful and Dynamic Frontend, idk there are many nore possibilities....

# Steps for First Use

python -m venv venv/      #Only for local machine

./venv/Scripts/activate      #Only for local machine

pip install -r requirements.txt

python manage.py makemigrations

python manage.py migrate

python manage.py createsuperuser

python manage.py migrate

python manage.py runserver   # For local machine

python manage.py runserver 0.0.0.0:8000 # For Cloud based instance



# Steps for further use like everytime after intial steps

python manage.py migrate

python manage.py runserver   # For local machine

python manage.py runserver 0.0.0.0:8000 # For Cloud based instance




# For Admin Account, please create one with superuser!

python manage.py createsuperuser

after that enter username, email and password of choice and then you are good to go.
