## What is this repository for? ##
* Use Google SpeechToText API to convert audio files (voicemails) into text and store into a relational database (MYSQL).

## Set up Videos ##
* [Docker](https://link.us1.storjshare.io/jv6xgubt4ymmy56qxtdrhwtsyila/lcubestudios%2FClients%20recordings%2FSlingshot%2FSlingshot_Docker_Demo.mp4)
* [AWS AMI](https://google.com)
* [Bitbucket/Github](https://google.com)

## General & Database Configurations ##
There are only two .env that need or can be modified. They are located in the parent path and inside the app folder

## Dependencies Required ##

### Stand alone Linux Server ###
* python3
* pip3
* php
* bash
* apache

### Linux Server with Docker ###
* Docker Compose 

### Test Enviroment ###
* The docker compose file will Containerize the application inside the app folder which runs (php,apache,python,bash)
* Create a database using MYSQL latest image while loading the pre-default schema
* Set up PHPMYADMIN 

### Set up Enviroment ###
* Update configuration file (.env). Change variable values to your need.
* Comment line 3 to 29 from the docker-compose.yml file when using a production enviroment
* Run docker compose up -d --build

### Deployment instructions ###
## Docker ##
* Update .env file
* Run docker compose up -d --build
* Build docker image 


## AWS AMI ##
* [Replicate AWS AMI](https://google.com)

## Bitbucket/Github ##
* Cloning
* installing 

### Useful Links ###
* [Google SpeechToText Product Information](https://cloud.google.com/speech-to-text)
* [Google Quick Start Guide](https://cloud.google.com/speech-to-text/docs/libraries)
* [Share an AMI with specific organizations or organizational units](https://docs.aws.amazon.com/AWSEC2/latest/WindowsGuide/share-amis-with-organizations-and-OUs.html)
* [Docker Hub](https://www.docker.com/products/docker-hub)


### Who do I talk to? ###
* Business Name: LCube Studios, LLC
* Emai: Contact@lcubestudios.io
* Website: [LCubestudios.io](https://Lcubestudios.io)
* Ask for our backend team