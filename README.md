### INF601 - Advanced Programming in Python
### Nicholas Kitchen
### Mini Project 4
 
 
# Project Title
 
Mini Project 4 - Zooventory
 
## Description
 
Zooventory is an application that makes tracking animals and food easy. After getting signed up and logged in, the user can add animals and food items. The user can also edit and delete the animals and food items if needed. Whenever the user feeds an animal, they will use the calculator. The calculator does 2 things:
1. It will subtract the entered amount from the food supply.
2. It will log the last time an animal has been fed.
 
## Getting Started
 
### Dependencies
 
Please install all the required packages:
```
pip install -r requirements.txt
```
 
### Installing

Please run the following command to move your working directory into the project:
``` 
cd ./miniproject4NicholasKitchen
```

Please create the database and migrate it into the project:

``` 
python manage.py makemigrations
```

``` 
python manage.py migrate
```

Please create your admin user. You will need to enter a username and password. Email is optional:

``` 
python manage.py createsuperuser
```

### Executing program

Please enter the following into the console to run the server:
```
python manage.py runserver
```

*If an error appears saying you cannot access that port, try running a different port. For example:*
```
python manage.py runserver 8001
```

### Routes

'server_url/' will take you to the login / signup page for Zooventory.
'server_url/admin' will take you to the admin portal.

## Authors
 
Nicholas Kitchen
 
## Version History

* 0.1
    * Initial Release
 
## Acknowledgments

* [Django](https://docs.djangoproject.com/en/5.2/)
* [Jinja](https://jinja.palletsprojects.com/en/stable/)
* [ChatGPT](https://chatgpt.com/g/g-p-6909265d38548191ae765ab1f4629cef-miniproject4nicholaskitchen/project)
