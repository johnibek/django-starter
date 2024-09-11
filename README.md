# **Django Starter README**

## Description

**_It serves as a foundation to django projects. It simplifies the process which is general for every project. 
So you can build your project upon it. As a result, you can save your precious time you spent doing the same thing to begin your every django project._**

## Prerequisites

### Create virtual environment and activate it
```shell
python3 -m venv venv
```
`Linux/Mac`
```shell
source venv/bin/activate
```
`Windows`
```shell
.\venv\Scripts\activate.bat
```
### Install requirements
```shell
pip install -r requirements.txt
```

#### Customize the database settings in `settings.py` file according to your project's scale. It has been set to SQLite by default.

### Make migrations
#### Inside a directory where `manage.py` file resides, run this commands:
```shell
python manage.py makemigraions
python manage.py migrate
```

#### Heroku basic settings are also provided for convenience!