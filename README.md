# Python Web Frameworks

These are just 3 web frameworks for Python applications, there are others, but these might be considered the "big 3" there is no ranking here though, each has its advantages and disadvantages.

## Flask

Flask is a web framework that is very lightweight, often referred to has
"batteries not included".  In order to follow this
[tutorial](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-now-with-python-3-support),
do these things first in the `flask` directory (ignore the `%` that is just my
prompt)

    % python3 -m venv .venv --prompt=test-flask
    % .venv/bin/activate
    (test-flask) % python3 -m pip install flask

You only need to install Flask once with pip but you'll need to activate the virtual environment every time you want to work on it or install any new package, this is the second line:

    % .venv/bin/activate

You can always tell you are in a virtual environment because of the prepended `(test-flask)` here.  You can change that in the `--prompt` command, there is nothing special about `test-flask` but you have to set this when you create the virtual environment, if you don't set it, the prompt will usee the name of the virtual environment directory.

Once you have activated the virtual environment issue the command

    (test-flask) % flask run

then navigate to `http://127.0.0.1:5000/`.  You can follow the tutorial from here.   Once you are finished working remember to deactivate the virtual environment by issuing the command

    (test-flask) % deactivte
    %

## Django

Django is a heavyweight/battries included web framework.  In order to follow this [tutorial](https://docs.djangoproject.com/en/3.1/intro/tutorial01/) do these things first in the `django` directory:

    % python3 -m venv .venv --prompt=test-django
    % .venv/bin/activate
    (test-django) % python3 -m pip install django
    (test-django) % cd mysite
    (test-django) % python manage.py runserver

then navigate to `http://127.0.0.1:8000/`.  You can follow the tutorial from
here.   Once you are finished working remember to deactivate the virtual
environment.

NOTE: If you read the tutorial like you'll see the command

    % django-admin startproject mysite

This has already been run for the files in this project but if you are starting
completely new then you'll need to run that command.

## Pyramid

Pyramid is another web-framework that occupies something of a middle ground
between Flask nad Django in terms of what it provides out of the box.  In order
to follow this
[tutorial](https://docs.pylonsproject.org/projects/pyramid/en/latest/narr/firstapp.html)
do these things first in the `pyramid` directory:


    % python3 -m venv .venv --prompt=test-pyramid
    % .venv/bin/activate
    (test-pyramid) % python3 -m pip install pyramid
    (test-pyramid) % python hello-pyramid.py

this will not pring anything in the console but you can navigate to then
navigate to `http://127.0.0.1:6543/` or `http://localhost:6453` to see the
output.  You can follow the tutorial from here.   Once you are finished working
remember to deactivate the virtual environment.
