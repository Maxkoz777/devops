# Moscow time demonstration

## Overview

This web-application is created to let the user be aware of the current time in Moscow. Every time you update the page, it shows you the actual time in the capital of Russia.

## Build and Run

Firstly, you have to clone current project via command:  
`$ git clone https://github.com/Maxkoz777/devops.git`  
Secondly, you have to change working directory by command:  
`$ cd app_python`  
Install requirements.txt file with dependencies:  
`$ pip install -r requirements.txt`  
After that you should install [Flask](https://phoenixnap.com/kb/install-flask) and [Gunicorn](https://flask.palletsprojects.com/en/2.2.x/deploying/gunicorn/)  
Then you have to execute command in the project root in terminal:  
`$ gunicorn -w 4 'app:app'`  
Finally, the application will be up and running [here](http://127.0.0.1:8000)

### Docker approach

* download [docker](https://www.docker.com)
* run commands from the section above if you haven't cloned this repository yet:  
  `$ git clone https://github.com/Maxkoz777/devops.git`  
  `$ cd app_python`
* run command:
  `$ docker-compose up`
* application will be up and running [here](http://127.0.0.1:8081)
* to stop current application run:
  `$ docker-compose down`


## Contact

You can contact me via telegram: **@maxkoz666**

