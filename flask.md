# FLASK  USING SQLITE3

This is the repository that contains the code for the Flask web app.This app is built for displaying and editing the student data in database

### Table of Contents
* [Getting Started](#getting-started)
* [Prerequisites](#prerequisites)
* [Installing](#installing)
* [Approach Towards The Development of Code](#approach-towards-the-development-of-code)
* [Setting up Development Environment and Execution](setting-up-development-environment-and-execution)
* [Built With](#built-with)
* [Author](#author)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for the development and test purposes.

### Prerequisites
* [Python](https://www.python.org)

### Installing

**Install with pip**
To work on Flask Microframework,first you should install flask and virtualenv and some more using pip in your windows command prompt

```
pip install flask
pip install virtualenv
pip install werkzeug
pip install jinja2
```

## Approach Towards The Development of Code

**Problem in creating web app**

1. Gives you different types of errors like UnboundLocalError while inserting/adding the new data into the database.

2. Gives you template not found error when you call html code in your program.

3. Gives You an exception when you didn't add any data in inserting page.

**APPROACH TOWARDS THE PROBLEMS**

1. By creating a templates folder to all html files you can avoid template not found error.

2. UnboundLocalError can be solved by assigning argument to None(e.g. msg=None)

3. We can avoid an exception by using try ,except and finally.

## Setting up Development Environment and Execution

Converting production environment to development environment with below step

```
set FLASK_APP=filename.py
set FLASK_ENV=development
```

**Execution**

```
flask run
 * Serving Flask app "prg1.py" (lazy loading)
 * Environment: development
 * Debug mode: on
 * Restarting with stat
 * Debugger is active!
 * Debugger PIN: 157-920-307
 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
 ```

### Built With

[Python](https://www.python.org)

### Author

Mounika Mandha

## Thank You
