#Dartmouth Hacker Club: A Flask Tumblelog
=================

The source code for the [Write a Tumblelog Application with Flask and MongoEngine](http://docs.mongodb.org/manual/tutorial/write-a-tumblelog-application-with-flask-mongoengine/)
tutorial.

This tutorial will ignore the database part and the css styling options
to limit the scope of the focus to the structure of the basic Python web 
framework. 

###Download and installation

#####Easy Way (if you don't know git)
On the right side of this page, click on the **Download ZIP** file. 
Extract the file and place it in your desired directory.

#####Better Way
Use GIT.

####Installation
*cd* into the root directory (of this project)
and install the requirements of this project

	pip install flask
	pip install flask-script
	pip install WTForms
	pip install mongoengine
	pip install flask_mongoengine

if this doesn't work use the following

	sudo -i
	pip install flask
	pip install flask-script
	pip install WTForms
	pip install mongoengine
	pip install flask_mongoengine

####Running
Go to the **tumbelog** folder

Run the tumblelog:
   
    python manage.py runserver

Goto: 
[admin site](http://0.0.0.0:5000/admin)
    username: admin
    password: secret
