# Getting started With Flash

## Install virtualenv:

Now that you have pip installed and a command prompt open installing virtualenv to our root Python installation is as easy as typing:

> pip install virtualenv

Now we have virtualenv installed which will make it possible to create individual environments to test our code in.

## Install virtualenvwrapper-win:

This is the kit and caboodle of this guide.

> pip install virtualenvwrapper-win

Excellent! Now we have everything we need to start building software using python!

## Every Project follow these 7 Steps:

### Make a Virtual Environment:

I'll call it ```HelloFlask```

**Not working**

> mkvirtualenv HelloFlask

---------------------------

> py -m venv env

> env\Scripts\activate

> pip install flask

> set FLASK_APP=app.py

> set FLASK_DEBUG=1

> flask run