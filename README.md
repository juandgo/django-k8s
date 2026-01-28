Comando para ejecutar el archivo requiremnts.txt

pip install -r requirements.txt

Comand to create a virtual enviroment:

python3 -m venv venv

comand to activate the eviroment

source venv/bin/activate

TO deactivate:

deactivate 

Comand to start a new django project

django-admin startproject django_k8s .

To create a workspace you have to go to file>save workspace as

Comand to run the server:

python manage.py runserver

Django commands

python manage.py collectstatic --noinput
python manage.py makemigrations # local change
python manage.py migrate --noinput


/opt/venv/bin/python manage.py migrate --noinput
python manage.py createsuperuser --email YOUR_EMAIL --noinput

