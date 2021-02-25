# Spotify_Music_Controller

Project on Django (backend) and React (frontend).

Code for controlling your spotify music remotely.
You need to add your CLIENT_ID and CLIENT_SECRET in the credentials.py under spotify folder. These you get from spotify's developer website after creating a account and an app.

To let users within your network join add the system's IP address in 'ALLOWED_HOST' list in settings.py under music_controller folder.

## Setup Instructions

Python packages required:
 ```bash
 pip install django
 pip install djangorestframework
```

### Start Web Server

To start the web server you need to run the following sequence of commands.

First cd into the folder
```bash 
cd "music_controller"
```
Next run the django web server.
```bash
python manage.py runserver
```

### Install Node Modules

First cd into the ```frontend``` folder.
```bash
cd frontend
```
Next install all dependicies.
```bash
npm i
```

### Compile the Front-End

Run the production compile script
```bash
npm run build
```
or for development:
```bash
npm run dev
```
