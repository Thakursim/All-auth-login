# Login with email.
 
This applications helps you to login and logout using email-id. 
It is made with the helpp of django. 

Clone this repository using this command:-

   `git clone https://github.com/Thakursim/All-auth-login`

# Getting up and running.
`cd Login`

This steps below will get you up and running with a local development environment. We assume you have the following installed:

  - pip
  - virtualenv
First make sure to create and activate a virtialenv, then open a terminal at the project root and install the requirements for local development.

    $ pip install -r requirements.txt 

When you have installed all the required modules, get inside the config folder using this command. 

`cd config`

Now you have to run a command to create a super user in the database. 
```sh
$ python manage.py createsuperuser
```
  You have to give a username, email address, and a password. By doing this you are good to go for the next step. 
 After getting inside of the login_logout folder run this command to open the web page on the browser. 
 ```sh
 $ python manage.py runserver
 ```

- Copy the http address visible on your shell, while pasting it in yor browser you can see that you have 2 options(Log In, Sign Up) available as you are not logged in.
- You can Log In with your email-id or Sign Up using different email-id. 
Login there with your credentials. 
- After logging in you can see a page welcoming you. And there will be a **Log Out** link available. You can log out by clicking on that.
- Then a page will appear for confirming that, Are you sure to sign out?. You can change the email, and sign up as new from this page only, there are options available. 
- After sign out, you will be again taken back to the 1st page where you have started. 

