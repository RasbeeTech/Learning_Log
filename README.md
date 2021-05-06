# Learning_Log
 Online journal system.  

## About
Allows users to log the topics they're interested in and to make journal entries as they learn about each topic.  The Learning Log home page will describe the site and invite users to either register or log in.  Once logged in, a user can create new topics, add new entries, and read and edit existing entries.  

## Technologies
Python: v 3.8.8  
Django: v 3.2  
Django-bootstrap: v 3.0.1  

## Run()

### Local:

1. Download project.  

2. In terminal, navigate to the project directory and create a Virtual Environment:  

```bash
 $ python3 -m venv ll_env
``` 

3. Activate the virtual environment:  

```bash
$ source ll_env/bin/acivate
```
note: To deactivare the virtual environment, use the command: 'deactivate'.  

4. If 'django-bootstrap' isn't already installed, enter the following command while in the 'll_env':  

```bash
 pip install django-bootstrap4
```

5. Initiate the database with the command:

```bash
# First:
 python manage.py makemigrations learning_logs
 
# Then:
 python manage.py migrate
```

6. Start the local server:

```bash
 python manage.py runserver
```

7.  With your choice of browser go your localhost:
```bash
# Option 1:
 http://127.0.0.1:8000/
 
# Option 2:
 http://localhost:8000/
```

## Sample
Home page:  

<img src='https://github.com/RasbeeTech/Learning_Log/blob/main/readme/images/home_page.png' title='home_page'>  

Login page:  

<img src='https://github.com/RasbeeTech/Learning_Log/blob/main/readme/images/login_page.png' title='login_page'>  

Registration:  

<img src='https://github.com/RasbeeTech/Learning_Log/blob/main/readme/images/register_page.png' title='register_page'>  

Topic page:  

<img src='https://github.com/RasbeeTech/Learning_Log/blob/main/readme/images/top_page.png' title='topic_page'>    

Topics page:

<img src='https://github.com/RasbeeTech/Learning_Log/blob/main/readme/images/topics_page.png' title='topics_page'>  
