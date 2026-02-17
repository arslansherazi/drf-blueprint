# Django Rest Framework Blueprint
### Pre-requisites
~~~
Python 3.14
~~~
~~~
UV Package Manager
~~~

### Setup project locally
~~~
uv venv --python 3.14 .venv
~~~
~~~
source .venv/bin/activate
~~~
~~~
uv sync 
~~~
~~~
uv sync --group dev
~~~

### Run local server
~~~
python manage.py runserver
~~~

### Admin Panel

### Database Migrations

#### Create a new migration
~~~
~~~
### Migrate
~~~
~~~

### Install a new python library
~~~
uv add <library_name>
~~~
### Install a new python library to a specific dependency group
~~~
uv add <library_name> --group <group_name>
~~~
### Upgrade a python library
~~~
uv add --upgrade <library_name>
~~~
### Install pre commit hooks
~~~
uv add pre-commit
pre-commit install
pre-commit autoupdate
~~~
 
