# recipe-django-rest

# Process followed to create and configure this application

### Step 1
Created the complete Dockerfile 

### Step 2
Created the requirements file and added the requirements

### Step 3
Executed the docker file by using the following command 
```docker build .```
This command build the docker in the existing WORKDIR

### Step 4
Created the docker compose file 

### Step 5
Executed the docker compose build command
```docker-compose build```
This command does not return anything but the project gets created

### Step 6 
Created a django application by using the following command 
```docker-compose app sh -c "django-admin startprojecr app ."```
Here app is the name of the service which came from docker-compose file

### Step 6
Executed the below command and the django app started
```docker-compose up```

## Completed First Commit 

## Travis CI integration and flake 8 integration

### Step 1
Created a travis.yml file in the project directory 

### Step 2 
Activated the travis CI account and integrated it with the repo 

### Step 3

Implemented flake8. Some problem hence removed it. Will execute it later

### Step 4
Added code and commited and pushed. The pipeline is automitacilly triggred on travis. You can directly check on the travis account.
https://app.travis-ci.com/github/nikhilgarware/recipe-django-rest 
