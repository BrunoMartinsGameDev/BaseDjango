# DJANGO BASIC CONFIGS
## Install the requirements
* Execute the following commands below:
```
python -m venv venv
```
```
venv/Scripts/activate
```
```
pip install -r requirements.txt
```
## Creating an app:
* Execute the command:
```
python manage.py startapp appName
```
* Change the app's name on the INSTALLED_APPS variable
* Chage the app's name inside the include on urls.py


## Things you can't forgot in your app
* Create the urls.py file inside your app 
* Create the variable ```app_name = 'appName'``` inside the urls.py
* Create the following folders templates/appName/index.html inside your app's folder
