# Overview
This is a php7.3 lamp environment created in docker to facilitate scaffolding symfony projects. This repo does NOT create any symfony5 code it is just the environment to run everything in. Once you have the docker containers running you can then CREATE your symfony app or run any PHP7 scripts in the DocumentRoot folder. 

# docker-symfony-ready
 - php73
 - mysql5.7
 - phpmyadmin-latest
 - apache2.4
 - symfony5
 - composer-latest
 - symfony-cli
 - all symfony5 required php-extensions

# Pre-requisite
1. Docker must be installed https://www.docker.com/get-started/ // Was made using Docker on Hyper-Visor but should work on any docker engine

# Setup and Config
1. Clone or download this repo
2. Navigate to the repo folder on your local computer
3. Setup your DB config in docker-compose.yml 

# Run the environment
1. Run "docker-compose up -d" in powershell or "docker-compose up -d" on unix

# Shutdown the environment 
1. docker-compose stop in powershell or "sudo docker-compose stop" on unix

# Accessing the Site / App
1. In browser localhost will go to the index.php page 
2. In broder localhost:8081 will go to phpmyadmin
