# django_tutorial

## Tutorial

* https://docs.djangoproject.com/en/2.2/intro/tutorial01/

## setup

* https://medium.com/@diwassharma/starting-a-python-django-project-on-mac-os-x-c089165cf010

### setup dev host

```
brew install python3
python3 --version
sudo pip3 install virtualenv
```

### setup project initial

```
virtualenv venv -p python3
source venv/bin/activate
deactivate
pip install Django==2.2.6
django-admin.py startproject django_tutorial
python manage.py startapp polls
python manage.py runserver
```

### setup project after checkout


## setup IDE 
* https://www.jetbrains.com/help/pycharm/creating-and-running-your-first-django-project.html
