# lms

Set up stage on local
1 - Install python and pip on computer and in visual studio
Open your project folder in Terminal
2 - Install Virtual environment "pip install virtualenv"
3 - Create virtual environment by name venv "python -m virtualenv venv
Will get an error so to solve that error open powershell as administrator and execute a command "Set-ExecutionPolicy Unrestricted -Force"
4 - Activate the virtual environment "./venv/Scripts/Activate"
5 - "python.exe -m pip install --upgrade pip"
6 - Now install the requirements from the requirements.txt file "pip install -r requirements.txt"
7 - Pillow and some requirements won't install then install them individually and delete those files from the requirements.txt "pip install pillow"
8 - Now run server by "python manage.py runserver"
9 - Now few modules will not install make them install like (django-unfold whitenoise)
"pip install django-unfold"
"pip install whitenoise"
10 - Now run server by "python manage.py runserver"
Congrates your project starts running.
#   n e w - t k  
 