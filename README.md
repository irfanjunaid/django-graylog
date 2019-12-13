# graylog-django-demo
Django demo app to send logs to remote graylog server through UDP

## Setup

### a. Install modules
pip install -r requirements.txt

### b. Setup Graylog
Setup this input: GELF-UDP

## Run the app
python manage.py runserver

## See the logs
Use graylog stream to see the logs in realtime