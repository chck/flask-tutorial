# flask-tutorial
ref. https://flask.palletsprojects.com/en/1.1.x/tutorial/

## Requirements
```
pipenv>=2018.11.26
direnv>=2.20.*
```

## Set the environment values
```
vi .env
=====================
FLASK_APP=flaskr
FLASK_ENV=development
```

## Usage
```
# Install dependencies
pipenv install

# Initialize the database
pipenv run init-db

# Run the application
pipenv run flask
```
