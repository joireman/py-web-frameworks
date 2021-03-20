# Python Web Frameworks

These are just 3 web frameworks for Python applications, there are others, but these might be considered the "big 3" there is no ranking here though, each has its advantages and disadvantages.  

## Flask

Flask is a web framework that is very lightweight, often referred to has
"batteries not included".  In order to follow the full
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

Django is a heavyweight/battries included web framework.  In order to follow the full [tutorial]() do these things first in the `django` directory: 

    % python3 -m venv .venv --prompt=test-django
    % .venv/bin/activate
    (test-django) % python3 -m pip install django



## Pyramid

    % python3 -m venv .venv --prompt=test-flask
    % .venv/bin/activate
    (test-flask) % python3 -m pip install flask

