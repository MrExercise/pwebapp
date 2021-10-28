# Web App Project

This project is a Python web application built using Flask microframework. You should be able to access it via localhost in your browser. The user can log in and out and create/edit articles.

## Log In Credentials for FlaskWebProject

- Username: admin
- Password: pass

## Instructions

-	Please create a Linux VM server and then setup the Python webapp with all the needed libraries and dependencies.

-	Setup a Postgres database in the same server.

-	Connect the flask app with a Postgres database (there is a default db used in code, it should be replaced with your own Postgres).

-	Version choice is up to you.

-	To prove that the application is working properly, go to the URL of your deployed app, login using the credentials (ignore the msal auth implementation in the code, just use the hardcoded credentials), click the Create button and create an article. The article should be able to save it, edit it or delete.

-	Once the app is up and running you should be able to see in the app's Log stream one potential form of logging with an "Invalid login attempt" and "admin/user logged in successfully".

-	To be able to containerize the app and the database it is not a must. It will be a significant plus if you manage to implement it.
	
-	You should be able to give a short description of the project you have created and explain choices you made.

## Dependencies:

-	Use of Virtual Machine (your choice)
-	Linux OS (your choice)
-	Python (3.8)
-	Flask webapp
-	Postgres database (version your choice)
-	Docker optional
-	Github repository optional
