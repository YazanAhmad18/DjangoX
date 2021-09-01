# Lab: 29 - DjangoX

## Summary:

### follow the repo [DjangoX](https://github.com/wsvincent/djangox) template to create a CRUD project .

### Some of those common tasks are…

* Create a custom user
* Configure static assets
* Add authentication
* Set up styling
* Install common libraries
* Wire up 3rd party development tools

### Repeating these steps over and over violates the DRY (Don't Repeat Yourself) rule. So pro developers usually create a skeleton application they use to start off their projects.

## Getting Run

```py
poetry init -n

poetry add --dev black flake8

poetry install

poetry add Django django-allauth django-crispy-forms django-debug-toolbar whitenoise

poetry shell

python manage.py migrate

python manage.py runserver
```
