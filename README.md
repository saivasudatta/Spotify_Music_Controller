# Spotify_Music_Controller

Code for controlling your spotify music remotely.

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
