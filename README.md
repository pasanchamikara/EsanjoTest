# Esanjo Python Assignment

This sample app has been designed with the aid of python's flask framework. The main reason for using this had been it's lightweightness.

The details regarding the deployment on development server are as follows. For Production environment the FLASK_ENV variable can be set to production and the deployment can begin.The App can be deployed within an app service from a given cloud solutions provider.

References:- For the Auth Services Design https://github.com/miguelgrinberg/REST-auth this repository had been used.

## Installation - Development
In this repository I have configured a python3 virtual environment. Therefore it would have all it's dependencies.

What you would all need to do is download the repository using 
```
$ git clone https://github.com/CaesarPrime/EsanjoTest.git
```

Then activate the virtual environment using 

```
$ . venv/bin/activate 
```
if you are using a linux based or MacOS Operating system

once done setup the environment variables needed within the virtual environement. As the task would be done within the development environemnt it is essential to mention that as well.

```
$ export FLASK_APP=Organizer.py
$ export FLASK_ENV=development
$ flask run
```

Once done the server would listen on http://localhost:5000

## Task 1

Use http://localhost:5000/task1 to access the task. Data needed for the processing were imported from the json 

## Task 2

Use http://localhost:5000/task2 to access the task. 


## Acknowledgements
1. [Miguel Grinberg's] (https://github.com/miguelgrinberg) [Flask authentication app repository](https://github.com/miguelgrinberg/REST-auth)
