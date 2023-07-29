## Nginx

Install Nginx reverse proxy to make this application available

`sudo apt-get update`
`sudo apt install nginx`


# Simple Notes App
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
--------------

NGINX ACESS LOGS(/var/log/nginx/access.log)




<img width="960" alt="na-1" src="https://github.com/iamsouvik9/django-notes-app/assets/79768737/8b15d511-567f-4e41-a454-7bbb83703976">

--------



NOTES-APP DASHBOARD




<img width="960" alt="na-2" src="https://github.com/iamsouvik9/django-notes-app/assets/79768737/df3612eb-0763-4114-9d12-054d607b6c9d">


