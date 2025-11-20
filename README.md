I worked on a Django Notes App where I dockerized the entire stack.
I forked the source code, built a Docker image for Django using Gunicorn, created separate containers for MySQL and Nginx, and orchestrated them using Docker Compose.
Nginx acted as a reverse proxy to forward requests to Gunicorn, and MySQL handled persistent storage.
The project allowed me to understand container networking, service dependencies, environment configuration, and production deployment patterns.

🚀 Project Overview: Django + MySQL + Nginx (Dockerized)

1. Django (Backend Application)
2. MySQL (Database)
3. Nginx (Reverse Proxy + Static File Server)


# Simple Notes App for TWS Community
This is a simple notes app built with React and Django.

## Requirements
1. Python 3.9
2. Node.js
3. React

## Installation
1. Clone the repository
```
git clone https://github.com/LondheShubham153/django-notes-app.git
```

2. Build the app
```
docker build -t notes-app .
```

3. Run the app
```
docker run -d -p 8000:8000 notes-app:latest
```

## Nginx

Install Nginx reverse proxy to make this application available

`sudo apt-get update`
`sudo apt install nginx`






