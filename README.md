# Django Project - Ecommerce

## Project Requirement
The laboratory work includes developing E-commerce applications. The students are highly
encouraged to use server side and client side scripting for developing the applications with
categories, shopping carts, payment gateways. Students can also use open source ecommerce
CMS frameworks and configure them to simulate e-commerce systems. The laboratory work
for e-comerce optimization includes SEO tools like Google Analytics, Facebook Analytics,
Twitter Analytics etc. Students can also implement basic recommendation system in the e-
commerce systems.

## Django
Django is a high-level Python web framework that encourages rapid development and clean, pragmatic design.
Django is a Python-based free and open-source web framework that follows the model–template–views architectural pattern.

## Virtual Environment (virtualenvs)
Virtual environments, or "virtualenvs" are lightweight, self-contained Python installations, designed to be set up with a minimum of fuss, and to "just work" without requiring extensive configuration or specialized knowledge. virtualenv avoids the need to install Python packages globally.
virtualenv is a tool for creating isolated Python environments containing their own copy of python , pip , and their own place to keep libraries installed from PyPI. It's designed to allow you to work on multiple projects with different dependencies at the same time on the same machine.

## django-admin and manage.py
django-admin is Django’s command-line utility for administrative tasks.

In addition, manage.py is automatically created in each Django project. It does the same thing as django-admin but also sets the DJANGO_SETTINGS_MODULE environment variable so that it points to your project’s settings.py file.

The django-admin script should be on your system path if you installed Django via pip. If it’s not in your path, ensure you have your virtual environment activated.

Generally, when working on a single Django project, it’s easier to use manage.py than django-admin. If you need to switch between multiple Django settings files, use django-admin with DJANGO_SETTINGS_MODULE or the --settings command line option.

The command-line examples throughout this document use django-admin to be consistent, but any example can use manage.py or python -m django just as well.

https://docs.djangoproject.com/en/3.2/ref/django-admin/

## Oscar
Oscar is an e-commerce framework for Django designed for building domain-driven applications. It is structured so that the core business objects can be customised to suit the domain at hand. In this way, your application can accurately model its domain, making feature development and maintenance much easier.

## Installing virtualenv

pip install virtualenv virtualenvwrapper

## Installing Oscar

pip install oscar

## Create django admin to create project

django-admin startproject my_site

## Changing settings.py file to integrate django oscar to our system

https://django-oscar.readthedocs.io/en/3.0.0/internals/getting_started.html

python manage.py makemigrations

python manage.py migrate

python manage.py runserver

## List virtaulenv
lsvirtualenv

## Activating virtualenv
[wilson@wilson-pc .virtualenvs]$ source oscar/bin/activate

https://uoa-eresearch.github.io/eresearch-cookbook/recipe/2014/11/26/python-virtual-env/

