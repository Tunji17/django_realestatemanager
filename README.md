<b><h1>Introduction</h1></b>
django_realestatemanager is a project that helps you manage real estate listings and agents. django_realestatemanager uses the             power of the Django framework.this project uses sqlite for the database but you can easily switch to mysql or postgres before             migration

<b><h1>Prerequisite</h1></b>
 - clone the repo
 - Create a virtual env <br>
 - install requirements.txt <br>        
        
       pip install -r requirements.txt
        
  
  
<b><h1>Installation</h1></b>
- create a postgres user and database and link it in the settings.py then run
    
       python manage.py makemigrations
        
       python manage.py migrate 
    
   to migrate the database 
   
<b><h1>Deployment</h1></b>
The project was deployed using Heroku, the live demo can be found at 

      https://django-realestatemanager.herokuapp.com/

  
