## REST API - CURD with PYTHON, DJANGO, REST Framework

![REST API PYTHON FLASK JWT](https://github.com/TravelXML/Create-API-PYTHON-PHP-NODEJS-GO-DJANGO-LARAVEL-LUMEN-REST-API/blob/main/PYTHON/images/Build%20REST%20api.png)


Create a RESTful web service for a Library. The service must have the following API endpoints:

    (C)reate a new Book
    (R)ead existing Books
    (U)pdate an existing Book
    (D)elete an existing Book

A Book entity has the following properties:

    Author (mandatory)
    Title (mandatory)
    ISBN (mandatory)
    Release Date

# Implementation(s)
  
  #### Create a project folder as 'rest-api'
  
       Go to project folder >> 'rest-api'
       
  #### Setup virtualenv in this project folder:
  
      $ pip3.8 install virtualenv
      $ virtualenv venv --python=python3.8
  
  #### Activate Virtual Environment
  
      $ source venv/bin/activate  - Mac / Linux 
        venv\Scripts\activate.bat - Windows
       
  #### Now, we can install Django:
       
      $ pip3 install django      
      
  #### Next, let’s start a new Django project:
      
      $ django-admin startproject msite
   
  #### If we look at the directory now, we’ll see that Django created a new folder for us:
  
      $ ls
        msite/     
     
  #### And if we look inside that folder, there’s everything we need to run a Django site:
      $ cd msite/
      $ ls
      manage.py*  msite/
  
   #### Let’s make sure it works. Test run the Django server:
   
      $ python3 manage.py runserver
      
      Watching for file changes with StatReloader
      Performing system checks...System check identified no issues (0 silenced).You have 17 unapplied migration(s). Your project may not work properly until you apply the migrations for app(s): admin, auth, contenttypes, sessions.
      Run 'python manage.py migrate' to apply them.May 17, 2019 - 16:09:28
      Django version 2.2.1, using settings 'msite.settings'
      Starting development server at http://127.0.0.1:8000/
      Quit the server with CONTROL-C.
      
   #### Go to localhost:8000 and you should see the Django welcome screen!
   
   
   #### Download from github and replaced with msite folder of rest-api root folder
      
     $ cd ..
    
   Download the msite folder from github and replaced with msite folder of rest-api root folder, once you are done with it.
    
    cd msite
   
   #### Ready to up server
   
    $ python3 manage.py runserver
    
    
   
   
  **Python Version: 3.8** <br/>
  
   
  **Request :** All request should be JSON data<br/>
  
  **Response :** JSON data<br/>

Enjoy coding! :)<br/>

#### For Support, you can reach me 
-------------------------------
#### Skype: sapan.mohannty
#### Twitter: https://twitter.com/htngapi
#### Linkedin: https://www.linkedin.com/in/travel-technology-cto/
