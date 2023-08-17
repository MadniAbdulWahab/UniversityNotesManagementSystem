# fyp
Create virtual environment
python -m venv venv

Activate virtual environment
.\venv\Scripts\activate

Install Requirements
pip freeze > requirements.txt
pip install -r requirements.txt 


Run Server
python manage.py runserver

DB Changes
python manage.py makemigrations
python manage.py migrate

Create super user
python manage.py createsuperuser


