# Django REST Framework Chat App project
Chat Application built using Django REST Framework

## Project Setup
 - Clone Project or download as zip file.
 ```bash
 git clone https://github.com/Marvellous-Chimaraoke/ChatApp-project.git
 ```
 - Create and activate virtual environment.
 ```bash
 pip3 install pipenv
 pipenv shell
 ```  
 - Install requirements.
 ```bash
 pipenv install
 ```
 - Run migrations to create database tables.
 ```bash
 python manage.py makemigrations
 python manage.py migrate
 ```
 - Run Project Server.
 ```bash
 python manage.py runserver
 ```

 ## Admin login
 - ```http://127.0.0.1:8000/admin```
    - Username: admin
    - Password: 1234