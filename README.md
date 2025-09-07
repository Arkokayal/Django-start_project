# Django-start_project
## How to creat a Django project
* Open a folder where you want to creat your project
* I choose **``` D:\vscode\django> ```**
* From that folder run the command prompt by typing **cmd** in place of path
* Farst you have to activate the Virtual Environment. by typing **activate**
* like **```D:\vscode\django>activate```**
* When command prompt is started creat a django project by the comand :- **django-admin startproject project_name**
* like **```D:\vscode\django>django-admin startproject start_pro```** my project_name is start_pro
* Then you have to get inside the project by the comand :- **cd projet_name**
* like **```D:\vscode\django>cd start_pro```** my project_name is start_pro
* Then you have to creat app by the comand :- **python manage.py startapp app_name**
* like **```D:\vscode\django\start_pro>python manage.py startapp app```**
* inside our project folder there is a settings.py file we have to open it and add our app_name inside the **INSTALLED_APPS** list
* like **```INSTALLED_APPS =["django.contrib.admin","django.contrib.auth","django.contrib.contenttypes","django.contrib.sessions","django.contrib.messages","django.contrib.staticfiles","app",]```**
## Now we have created our first procject✔✔✔🎊🎊🎊
