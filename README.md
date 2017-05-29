## Development

### Versions
Python 3.6.1  
Django 1.11.1

### Using Django

##### Create a new project

`$ django-admin startproject [project_name]`

##### Create a new app

`$ python manage.py startapp [app_name]`

##### Using Migrations

    # Store model changes as a migration
    $ python manage.py makemigrations [app]
    
    # Get SQL for migration
    $ python manage.py sqlmigrate [app] [migration_number]
    
    # Execute migration
    $ python manage.py migrate

### Using PostgreSQL
    
    # Launch in foreground
    $ postgres -D /usr/local/var/postgres
    
    # Create DB for user `ben`
    $ createdb ben
    
    # Connect to DB
    $ psql
    
    # Install AdminPack for PgAdmin
    $ psql postgres -c 'CREATE EXTENSION "adminpack";'

## Useful Links

* [Deployment Checklist](https://docs.djangoproject.com/en/1.11/howto/deployment/checklist/)
* [Outputting PDFs in Django](https://docs.djangoproject.com/en/1.11/howto/outputting-pdf/)
