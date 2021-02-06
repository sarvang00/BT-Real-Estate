# BT Real Estate
A project that involves listing of Real Estate sites and Realtors. Also involves the functionality that lets users log in.

## Requirements
1. Python 3.x
2. Postgres SQL Database
3. Python dependancies specified in requirements.txt

## Project Specifications
* Project front-end made using vanilla HTML5, CSS3 files.
* Django used as backed.
* Database used is PostgresSQL database.

## Importnant Note
* All files uploaded as it is a dev application. Files like settings.py in btre (project directory) need to be modified and variables like secret key need to be hidden.


## Database Setup
This project has been made in PostgresQL.

A database shall be required to be made in POSTGRES (version 10 and above supported) with the name of 'efiling'.

Then migrations will be required to be made.

Follow this command to create a note for changes and migrations.

```bash
python manage.py makemigrations
```

Resolve error messages, if any. Else continue to make migration to database:
```bash
python manage.py migrate
```

If you see no error messages, congratulations! Your project database has been successfully setup.

## Superuser and Groups setup

Once the database is setup, the first recommended step is to make a superuser.

That can be done by using the following command in the project terminal:
```bash
python manage.py createsuperuser
```
From here, you can follow the superuser instructions.

Now your app is ready in most spaces (and with some tweaks in your settings.py, for deployment!)


## Initial Setup

To use the application, the following command needs to be run:
```bash
python manage.py runserver
```

