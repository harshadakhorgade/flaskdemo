# flaskdemo
Building API using Flask

Summary:

Create an API using Python, Flask and its extension SQLAlchemy.

Files:

app.py - API source code

Create database use python command.Data.db - SQLite DB with one table 'Movie'. Its fields are -ID, Name, Genre, Language and IMDB rating.

requirements.txt - Packages needed to run this app. Ensure to 'pip install -r requirements.txt' in your projects virtual environment

Command:

sudo apt install python3.10

python3 --version

sudo apt install python3.10-venv

python3 -m venv env

. env/bin/activate

pip install flask

pip install flask-sqlalchemy

Set environment variables: FLASK_APP=APP and FLASK_ENV=development

flask run --host private ip --port 5000 --debug

The server runs on http://public:5000

Endpoints:

/movies - to GET and POST

/movies/ - to PUT and DELETE
