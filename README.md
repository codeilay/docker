# README #

This repository contains a Docker server structure designed to quickly deploy projects on a local computer.

**Default settings:**
* PORT: 3000
* HOST: localhost
The current settings can be changed in the file **docker-compose.yml**

**NGINX default settings:**
* INDEX: index.html
* ROOT: /var/www/html/
The current settings can be changed in the file **_docker/nginx/conf.d**

**To start a container:**
* Download the branch to your project folder on your local machine. Use in terminal `git clone git@github.com:codeilay/docker.git .`
* The public folder is the root folder in the project. Place the app inside the public folder.
* To start the server, use the npm "dev" command in the vscode or command in terminal `docker-compose up -d`
* The server starts on port 3000 at localhost. 

> http://localhost:3000

**To stop a container:**

Use command in terminal `docker-compose down`

## Branch Lite ## 

**Contains containers:**
* nginx
